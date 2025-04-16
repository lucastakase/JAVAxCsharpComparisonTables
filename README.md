# Java vs C# Syntax Comparisons

This repository provides a detailed comparison of **Java** and **C#** syntax across various concepts and constructs. The comparisons are organized into several key areas such as package declarations, data types, class declarations, and more.

## Overview

This project helps developers who are familiar with one language (Java or C#) transition to the other. The tables provide clear, side-by-side comparisons to highlight similarities and differences between the two languages.

## Sections Included:

- **Package and Namespace Comparison**  
  Comparison of how packages/namespaces are declared, used, and organized in Java and C#.

- **Data Types Comparison**  
  A comparison of primitive and object data types in both Java and C#, including handling of constants, null values, and default initialization values.

- **Class, Interface, and Member Comparison**  
  Comparison of how classes, interfaces, enums, and class members (like access modifiers, static members, constants, etc.) are declared and used.

- **Summary Table**  
  A consolidated summary of all the comparisons, providing a quick reference for the main points discussed.

## Table of Contents

### Core Concepts
- [Access Modifier Keyword Comparison](AccessModifierKeywordComparison.adoc)  
- [Type Declaration & Access Manipulation](TypeDeclarationAccessManipulationKeywords.adoc)  
- [Simple Types & Constants](SimpleTypeConstantKeywords.adoc)  

### Control Flow
- [Flow Control Keywords](FlowControlKeyword.adoc)  
- [Exception Handling](ExceptionHandlingKeywords.adoc)  

### Operators & Expressions
- [Operators Reference](Operators.adoc)  
- [Precedence & Associativity Rules](PrecedenceAssociativity.adoc)  

### Advanced Topics
- [Package/Namespace Management](PackageNamespaceKeywords.adoc)  
- [Unmanaged Code Keywords](UnmanagedCodeKeywords.adoc)  

### Overview
- [Summary of Concepts](Summary.adoc)

## Structure

The comparisons are presented in the following tables:

| Concept                           | Java                                   | C#                                      | Notes                                      |
|-----------------------------------|---------------------------------------|-----------------------------------------|--------------------------------------------|
| **Package and Namespace Comparison** | `package packageName;`<br>`import package.Class;` | `namespace NamespaceName;`<br>`using Namespace.Class;` | Used to organize and access external types. |
| **Data Types Comparison**          | `byte`, `short`, `int`, `long`, `float`, `double`, `char`, `boolean`, `String`, `final` | `byte`, `short`, `int`, `long`, `float`, `double`, `char`, `bool`, `string`, `const`, `readonly` | Differences in constant declaration, null handling, and primitives vs objects. |
| **Class, Interface, and Member Comparison** | `class ClassName`, `interface InterfaceName`, `enum EnumName`, `abstract class ClassName`, `private`, `public`, `protected`, `static`, `final` | `class ClassName`, `interface InterfaceName`, `enum EnumName`, `abstract class ClassName`, `private`, `public`, `protected`, `static`, `const`, `readonly` | Similar declarations, but differences in constant and read-only fields, access modifiers, and type checking. |

## Usage

You can navigate through the repository to review the full comparisons, or use the provided summary table to quickly grasp the differences.
