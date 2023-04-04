
# BlazorKit.CopyToClipoard

It's a beta version.

![demo](https://user-images.githubusercontent.com/2757486/229806262-d3b0ac5f-e6de-4e4f-8007-f22b97af1729.png)

## Features

- Customize CSS Class for button

## Installation

With Package Manager:

```gitattributes
Install-Package BlazorKit.CopyToClipboard
```

With .NET CLI:

```gitattributes
dotnet add package BlazorKit.CopyToClipboard
```

Add the following line to your Program.cs file

```gitattributes
builder.Services.AddScoped<IClipboardService, ClipboardService>();
```

Add the component to your page (take a look at the sample project)
```gitattributes
<CopyToClipboard Text="Hello World" />
```

## Run Locally

Clone the project

```gitattributes
  git clone https://github.com/kasuken/BlazorKit.CopyToClipboard
```

Go to the project directory

```gitattributes
  cd BlazorKit.CopyToClipboard
```

Start

```gitattributes
  dotnet run
```

## Contributing

Contributions are always welcome!
