[![NuGet](https://img.shields.io/nuget/v/swagger4wcf.svg)](https://www.nuget.org/packages/Swagger4WCF)
# Swagger4WCF

Swagger4WCF generate automatically swagger YAML to describe WCF services on project build time. It is used as nugget package to add build action that analyse output, find assembly and documentation to produce swagger YAML description thanks to Reflection API.

## アドホックな対応

- 異なる Framework Version (ex: .NET Framework 3.5) に対して実行できるように
- List<string> のような Generic な型でかつ型引数が一つだけのものに対して実行できるように
