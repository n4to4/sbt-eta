# sbt-eta Example Project

This project show cases a setup between Eta and Scala that you are free to use as a
template.

## Description

This project has two components: a Scala project and an Eta project. The Scala 
component will read from a file (`src/main/resource/data.json`) that has a json object
on each line. Each line will be sent over to the Eta component via FFI which will
process it and return the result back to Scala. Scala will then generate a file called
`output.json` which will be created wherever you have invoked `sbt run`.

## Running

To compile & run the project:

```shell
sbt run
```

## License

This example project is available under the MIT License, see [LICENSE](./LICENSE) for 
more information.