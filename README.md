# DropMerge

DropMerge is a simple yet powerful Windows application that allows users to merge multiple text files and count tokens using the Tiktoken library, which is compatible with OpenAI's GPT models.

## Features

- Drag and drop interface for adding files
- Supports any non-binary text file
- Merges selected files into a single output file
- Real-time token counting using Tiktoken
- Ability to remove selected files from the list
- Persistent settings between sessions

## Installation

1. Clone this repository or download the source code.
2. Open the solution in Visual Studio.
3. Restore NuGet packages.
4. Build and run the application.

## Usage

1. Launch the DropMerge application.
2. Drag and drop text files onto the application window.
3. The files will be listed in the right panel.
4. Set the output location by clicking the "Output Location" button.
5. Select files to remove them using the "Remove Selected" button if needed.
6. Click "Merge" to combine all listed files into the output file.

The token count for all added files is displayed at the bottom left of the window.

## Dependencies

- .NET 6.0 or later
- Tiktoken library



