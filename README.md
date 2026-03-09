# how to use

1. At the user or project level of your claude code settings, add this json block to your configs:

```
{
  "extraKnownMarketplaces": {
    "brad-marketplace": {
      "source": {
        "source": "git",
        "url": "https://github.com/white8785/brad-marketplace.git"
      }
    }
  }
}
```

2. Run claude code and run the `/plugin` command.
3. Go right until you see `Marketplaces`, and you should see `brad-marketplace`
4. `Enable auto-update` so the plugin stays up-to-date
5. Directly engage the agent by `@` mentions
6. Indirectly engage the agent by talking about documentation engineering
