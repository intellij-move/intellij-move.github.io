# Movefmt integration

The plugin features integration with [MoveBit's movefmt code formatter](https://github.com/movebit/movefmt).

## Download `movefmt` executable

Run

```bash
$ aptos update movefmt
```

Enter `Y` when prompted and wait for the download to finish.

Remember the path of the resulting binary at the end of the command output

```bash
Downloading...
Extracting archive... Moving binary file to ~/.local/bin... Done
{
  "Result": "Successfully installed movefmt v1.0.6"
}
```

> If you don't have an Aptos CLI installed,
> download `movefmt` executable
> from [Releases page of the official repository](https://github.com/movebit/movefmt/releases).

## Configure Move on Aptos plugin to use the formatter

Open **File | Settings...**, then select **Languages & Frameworks | Aptos | Movefmt**

![movefmt settings](movefmt_settings.png)

Select path of the `movefmt` binary in the `Movefmt:` field and enable `Use movefmt instead of the built-in formatter`.

## Usage

<procedure title="Reformat currently opened file" id="reformat_opened_file">
<step>Open the file you'd like to reformat.</step>
<step>Press <shortcut key="$ReformatCode"/> or select <b>Code | Reformat Code</b> from the main menu.</step>
</procedure>

![reformat code](reformat_code.gif)

<seealso>
<category ref="related">
    <a href="Code-Formatter.md">IDE built-in code formatter</a>
</category>
<category ref="external">
    <a href="https://aptos.dev/en/build/cli/formatting-move-contracts">Aptos Movefmt documentation</a>
</category>
</seealso>