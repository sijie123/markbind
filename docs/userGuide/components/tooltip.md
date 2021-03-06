## Tooltip

<tip-box border-left-color="#00B0F0">
  <i style="font-style: normal; font-weight: bold; color: dimgray">Example</i><br>
  <tooltip header content="Lorem ipsum dolor sit amet" placement="top">
    <button class="btn btn-secondary">Popover on top</button>
  </tooltip>
  <tooltip header content="Lorem ipsum dolor sit amet" placement="left">
    <button class="btn btn-secondary">Popover on left</button>
  </tooltip>
  <tooltip header content="Lorem ipsum dolor sit amet" placement="right">
    <button class="btn btn-secondary">Popover on right</button>
  </tooltip>
  <tooltip header content="Lorem ipsum dolor sit amet" placement="bottom">
    <button class="btn btn-secondary">Popover on bottom</button>
  </tooltip>
  <hr />
  Trigger
  <p>
    <tooltip effect="scale" content="Lorem ipsum dolor sit amet" placement="top" trigger="click">
      <button class="btn btn-secondary">Click</button>
    </tooltip>
    <tooltip effect="scale" content="Lorem ipsum dolor sit amet" placement="top" trigger="contextmenu">
      <button class="btn btn-secondary">Contextmenu (right click)</button>
    </tooltip>
    <br />
    <br />
    <tooltip effect="scale" content="Lorem ipsum dolor sit amet" placement="top" trigger="focus">
      <input placeholder="Focus"></input>
    </tooltip>
  </p>

  **Markdown**:
  <tooltip effect="scale" content="*Hello* **World**">
    <a href="">Hover me</a>
  </tooltip>
  <br />

  **Free Text**:
  <tooltip content=" coupling is the degree of interdependence between software modules; a measure of how closely
  connected two routines or modules are; the strength of the relationships between modules."><i>coupling</i></tooltip>
</tip-box>
<tip-box border-left-color="black">
<i style="font-style: normal; font-weight: bold; color: dimgray">Markup</i>

  ``` html
  <tooltip header content="Lorem ipsum dolor sit amet" placement="top">
    <button class="btn btn-secondary">Popover on top</button>
  </tooltip>
  <tooltip header content="Lorem ipsum dolor sit amet" placement="left">
    <button class="btn btn-secondary">Popover on left</button>
  </tooltip>
  <tooltip header content="Lorem ipsum dolor sit amet" placement="right">
    <button class="btn btn-secondary">Popover on right</button>
  </tooltip>
  <tooltip header content="Lorem ipsum dolor sit amet" placement="bottom">
    <button class="btn btn-secondary">Popover on bottom</button>
  </tooltip>
  <hr />
  Trigger
  <p>
    <tooltip effect="scale" content="Lorem ipsum dolor sit amet" placement="top" trigger="click">
      <button class="btn btn-secondary">Click</button>
    </tooltip>
    <tooltip effect="scale" content="Lorem ipsum dolor sit amet" placement="top" trigger="contextmenu">
      <button class="btn btn-secondary">Contextmenu (right click)</button>
    </tooltip>
    <br />
    <br />
    <tooltip effect="scale" content="Lorem ipsum dolor sit amet" placement="top" trigger="focus">
      <input placeholder="Focus"></input>
    </tooltip>
  </p>
  <h4>Markdown</h4>
  <tooltip effect="scale" content="*Hello* **World**">
    <a href="">Hover me</a>
  </tooltip>
  <br />
  <br />
  <h4>Free Text</h4>
  <tooltip content=" coupling is the degree of interdependence between software modules; a measure of how closely
  connected two routines or modules are; the strength of the relationships between modules."><i>coupling</i></tooltip>
  ```
</tip-box>

#### Tooltip Options

Name | Type | Default | Description
---- | ---- | ------- | ------
trigger	| `String` | `hover` | How the tooltip is triggered.<br>Supports: `click`, `focus`, `hover`, `contextmenu`.
content | `String` | `''` | Text content of the tooltip.
placement | `String` | `top` | How to position the tooltip.<br>Supports: `top`, `left`, `right`, `bottom`.