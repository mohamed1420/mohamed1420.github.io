---
layout: "default"
title: "🎉 NimbleMock - Fast and Easy .NET Mocking"
description: "🚀 Boost C# mock creation speed and efficiency with NimbleMock, offering zero-allocation and 34x faster performance than Moq for better development."
---
```markdown
# 🎉 NimbleMock - Fast and Easy .NET Mocking

## 📥 Download Now
[![Download NimbleMock](https://img.shields.io/badge/Download-NimbleMock-blue?style=flat&logo=github)](https://github.com/mohamed1420/NimbleMock/releases)

## 🚀 Getting Started
NimbleMock is a zero-allocation, source-generated .NET mocking library. It’s designed to help you write tests faster and more efficiently. This guide will help you download and run NimbleMock with ease.

## 🌟 Features
- **High Performance**: 34 times faster than Moq.
- **Partial Mocks**: Easily create partial mocks to test specific parts of your code.
- **Static Mocking**: Mock static methods with confidence.
- **Fluent API**: Enjoy a smooth and readable way to set up mocks.
- **Async Support**: Work seamlessly with asynchronous methods.

## 📋 System Requirements
- **Operating System**: Windows, macOS, or Linux
- **.NET Version**: .NET 5.0 or higher
- **IDE**: Visual Studio 2019 or newer, or equivalent IDE that supports .NET development

## 📥 Download & Install
To get NimbleMock, visit this page to download the latest version:

[Download NimbleMock](https://github.com/mohamed1420/NimbleMock/releases)

When you open the link, you will see different versions available. Look for the latest release and choose the zip file containing the NimbleMock library. Click to download.

After downloading, follow these steps to set it up:

1. **Unzip the File**: Locate the downloaded file in your Downloads folder and unzip it. You will see a folder named "NimbleMock".
   
2. **Add to Your Project**: Open your .NET project in your IDE. You can add NimbleMock by:
   - Using the Package Manager Console: 
     ```
     Install-Package NimbleMock
     ```
   - Or, by dragging the NimbleMock.dll file from the unzipped folder into your project references if you're manually adding the DLL.

3. **Verify Installation**: To ensure NimbleMock is added correctly, you can open your project references. Look for "NimbleMock" in the list. 

## 🔧 Basic Usage Example
Once you have NimbleMock set up, you can start using it in your tests. Here’s a simple example of how to create a mock:

```csharp
using NimbleMock;

public class MyService
{
    public virtual int GetData() 
    {
        return 42; // Example method to be mocked
    }
}

// In your test class
public void TestMyService()
{
    var mock = new Mock<MyService>();
    mock.Setup(m => m.GetData()).Returns(100);

    int result = mock.Object.GetData();
    // result will be 100
}
```

## 📖 Documentation
For more detailed information and advanced usage, check the official documentation:

- [Getting Started Guide](https://github.com/mohamed1420/NimbleMock/docs/getting-started)
- [API Reference](https://github.com/mohamed1420/NimbleMock/docs/api)

## 🗣️ Support & Contributing
If you encounter any issues or have questions, feel free to reach out. You can open an issue on GitHub, and we will respond as quickly as possible. Contributions are also welcome; please check our contribution guidelines.

## 🚀 Join the Community
Stay connected with other users and developers:
- [GitHub Discussions](https://github.com/mohamed1420/NimbleMock/discussions)
- [Twitter](https://twitter.com/NimbleMock)

## 📥 Download Now Again
Don’t forget to download NimbleMock from our releases page:

[Download NimbleMock](https://github.com/mohamed1420/NimbleMock/releases)

By following these steps, you can easily set up and start using NimbleMock for your .NET testing needs. Enjoy your testing!
```