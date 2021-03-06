# Karabiner config generator
> Small DSL to easily modify [Karabiner](https://github.com/tekezo/Karabiner-Elements) configuration

The idea is to make a small language with first class support for variables, sticky key and simultaneous key definitions that generates [Karabiner JSON](https://pqrs.org/osx/karabiner/json.html).

The script is a modified version of a [ruby script](https://github.com/pqrs-org/KE-complex_modifications/blob/master/src/json/personal_tekezo_launcher_mode_v4.json.rb) by [Tekezo](https://github.com/tekezo).

The [included script](karabiner-generate.rb) contains my own private keyboard configuration. To generate it and add it to Karabiner Elements, run this command:
`ruby karabiner-generate.rb | pbcopy`

This will put Karabiner JSON of all the rules in your clipboard. You can then paste it inside Karabiner in-between `rules []` block.

## Related
- [Karabiner JSON Spec](https://pqrs.org/osx/karabiner/json.html)

## Contributing
[Suggestions](../../issues/) and pull requests are highly encouraged!

## License
MIT © [Nikita Voloboev](https://nikitavoloboev.xyz)