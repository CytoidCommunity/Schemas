# Schemas

Community-maintained schemas for Cytoid-related JSON files

## How to use

1. Use a [compatible editor](https://json-schema.org/implementations.html#editors). Visual Studio Code is recommended.
2. Add a line to the head of your JSON file:

```json
{
  "$schema": "https://url/to/schema",
  "other_things": "go_here"
}
```

3. Enjoy the auto-completion!

> Well not really. What JSON Schema can provide is actually very restricted. If you use a better tool, continue using it! This schema is to help you to write correct Cytoid-specific JSON files by hand.

## Releases

**NOTE: Minimal version is preferred. It has smaller file size and makes computers smile.**

### level.json

| Version     | GitHub                                                                                                                                                      | Gitee (mirror)                                                                                                                                                    |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2.0 (Draft) | [raw](https://github.com/CytoidCommunity/Schemas/raw/master/2.0/level.json) [min](https://github.com/CytoidCommunity/Schemas/raw/master/min/2.0/level.json) | [raw](https://gitee.com/ZeroAurora233/CytoidSchemas/raw/master/2.0/level.json) [min](https://gitee.com/ZeroAurora233/CytoidSchemas/raw/master/min/2.0/level.json) |

### storyboard.json

| Version     | GitHub                                                                                                                                                                | Gitee (mirror)                                                                                                                                                              |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2.0 (Draft) | [raw](https://github.com/CytoidCommunity/Schemas/raw/master/2.0/storyboard.json) [min](https://github.com/CytoidCommunity/Schemas/raw/master/min/2.0/storyboard.json) | [raw](https://gitee.com/ZeroAurora233/CytoidSchemas/raw/master/2.0/storyboard.json) [min](https://gitee.com/ZeroAurora233/CytoidSchemas/raw/master/min/2.0/storyboard.json) |

## To-Dos

- [ ] Complete the schemas.
- [ ] Complete integrated documentation, default values and more.
- [x] Style the schemas using `Prettier` rather than the formatter included in Visual Studio Code.
- [ ] Publish the first release!
- [ ] Implement JSON Schema draft 2019-09 (after Visual Studio Code fully supports it).

## License

For your convenience, the schemas are in **public domain**, under CC0-1.0. However, we still hope you to credit us in the description of your level!
