# Static analysis

## Clang tidy

### How to configure a custom step in QT Creator?

Insert these 3 lines:

- `clang-tidy`
- `-p=%{buildDir} %{CurrentDocument:FilePath}`
- `%{buildDir}`

Then open any `cpp` file and run `Build`. Find clang warnings in the console output.
