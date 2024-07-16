# iex.exs
IEX shell configuration file

After pulling down this repo you can copy it to your home via

```bash
cp .iex.exs ~/.
```

And then in your project's `.iex.exs` you can import your global version at the top of the file via:

```elixir
# .iex.exs in project
import_file_if_available("~/.iex.exs")
```

**Note: to enable shell history you need to export the following env var:**
```bash
export ERL_AFLAGS="-kernel shell_history enabled" 
```
