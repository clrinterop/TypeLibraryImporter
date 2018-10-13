# Type Library Importer

> Tlbimp is a command line tool which creates a managed, interop assembly from a COM type library.

**TLBIMP** is a .NET SDK tool that creates an Interop assembly from a COM type library.
This project is a managed code implementation of **TLBIMP**.
We have released this tool so developers can see what **TLBIMP** does and if necessary
 extend the tool for their specific requirements.

A UI tool, **TlbimpRuleFileEditor**, can be found in the package for customization purpose,
which help to create a configuration file without requiring knowledge of xml configuration file syntax.

The package also includes some tests, which can be used with **Tlbimp Regression Test Tool**
(attached in the package as well) to validate any updates made against the original source code.
More information about this tool can be found in the document in the package.


## License

The **Type Library Importer** application is licensed under Microsoft Limited Public License (Ms-LPL).

Ms-LPL is based on Microsoft Public License (Ms-PL), but there is a Windows-platform limitation:
> 4. (F) Platform Limitation- The licenses granted in sections 2(A) & 2(B) extend only
> to the software or derivative works that you create that run on a Microsoft Windows
> operating system product.
