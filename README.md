# Components flowchart

This is a flowchart created using [mermaid](https://github.com/knsv/mermaid).

## Setup

1. Install [Mermaid Preview](https://github.com/vstirbu/vscode-mermaid-preview) VSCode extension
2. Open `COMPONENTS.md`
3. Go to Command Palette: <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>
4. Choose "Preview Mermaid"
5. Focus editor tab with chart

## Syntax

- Use `{rhombus}` for "root" components (with no component dependencies).
- Use `[square]` for "leaf" components (with no dependents).
- Use `(rounded square)` for intermediate components.
- Use `((circle))` for components with no dependencies / dependents.
- Use `>asymmetric shape]` for components with only one dependent.

## Tips

- Play with lines order. Sometimes reordering makes chart to be re-positioned.
  - Use "Move Line Down" / "Move Live Up": <kbd>Option</kbd> + <kbd>↓</kbd> / <kbd>Option</kbd> + <kbd>↑</kbd>
- Group root components at the top, and leaf components at the bottom.

## Links

- [mermaid flowchart syntax](https://mermaidjs.github.io/#/flowchart)
- [mermaid live editor](https://mermaidjs.github.io/mermaid-live-editor/)
- [mermaid configuration](https://mermaidjs.github.io/#/mermaidAPI?id=configuration)
