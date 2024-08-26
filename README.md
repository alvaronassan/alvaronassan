![](img/Elixir.png)

---

```elixir
defmodule Me do
  @moduledoc """
    user profile description
  """
  @type languages :: :elixir | :typescript | :ruby

  @type languages_spoken :: :pt | :es | :en

  @spec name() :: String.t()
  def name do
    "Álvaro Santana"
  end

  @spec favorite_languages() :: [languages]
  def favorite_language do
  [:elixir, :typescript, :ruby]
  end

  @spec technical_skills() :: [String.t()]
  def technical_skills do
    ["Phoenix", "Liveview","Ecto", "GrahQL", "Docker", "React", "Astro"]
  end

  @spec goals() :: map()
  def goals do
    %{
      :elixir => "I want to deepen my knowledge of the language and explore other areas of application.",
      :english => "I want to improve my communication and writing skills."
    }
  end

  @spec projects() :: map()
  def projects do
    %{
      :designo => "https://github.com/alvaronassan/designo",
      :myths => "https://github.com/alvaronassan/myths",
      :audiophile => "https://github.com/alvaronassan/audiophile",
    }
  end

  @spec hobbies() :: String.t()
  def hobbies do
    "Sometimes I write some horror tales, sometimes I draw"
  end
end
```
