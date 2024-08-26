![](img/Elixir.png)

---

```elixir
defmodule Me do
  @moduledoc """
    user profile description
  """
  @type languages :: :elixir | :typescript | :ruby

  @spec name() :: String.t()
  def name do
    "Alvaro Santana"
  end

  @spec favorite_languages() :: [language]
  def favorite_language do
  [:elixir, :typescript, :ruby]
  end

  @spec hobbies() :: String.t()
  def hobbies do
    "Sometimes I write some horror tales, sometimes I draw"
  end
end
```
