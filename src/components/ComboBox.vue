<template>
  <div
    style="
      --spectrum-popover-height: 142px;
      --spectrum-popover-width: 166px;
      position: relative;
      display: inline-flex;
      align-items: center;
      justify-content: center;
    "
  >
    <div
      class="spectrum-Combobox spectrum-Combobox--sizeM is-open"
      id="popover-trigger-kurty"
      data-testid="combobox"
      style=""
    >
      <div
        class="spectrum-Textfield spectrum-Textfield--sizeM spectrum-Combobox-textfield"
        style=""
        id="textfield-y25fg"
      >
        <input
          type="text"
          name="field"
          id="textfield-y25fg-input"
          class="spectrum-Textfield-input spectrum-Combobox-input"
        />
      </div>

      <button
        aria-haspopup="listbox"
        class="spectrum-PickerButton spectrum-PickerButton--uiicononly spectrum-PickerButton--right spectrum-PickerButton--sizeM is-open spectrum-Combobox-button"
        style=""
        id="picker-t5cez"
        tabindex="-1"
      >
        <div class="spectrum-PickerButton-fill">
          <svg
            focusable="false"
            aria-hidden="true"
            role="img"
            class="spectrum-Icon spectrum-UIIcon-ChevronDown100 spectrum-Icon--medium spectrum-PickerButton-icon"
            id="icon-bmd2m"
            aria-labelledby="Chevron100"
          >
            <title id="Chevron100">Chevron100</title>
            <use
              xlink:href="#spectrum-css-icon-Chevron100"
              href="#spectrum-css-icon-Chevron100"
            ></use>
          </svg>
        </div>
      </button>
    </div>

    <div
      role="presentation"
      class="spectrum-Popover is-open spectrum-Popover--sizeM spectrum-Popover--bottom-start"
      style="inset-block-start: 100%; inset-inline-start: 0"
      id="popover-ut3mn"
      data-testid="popover-ut3mn"
    >
      <ul
        class="spectrum-Menu spectrum-Menu--sizeM is-selectable"
        id="menu-khlld"
        role="listbox"
        aria-labelledby="menu-label-k85t1"
        aria-disabled="false"
        style=""
      >
        <li
          class="spectrum-Menu-item is-selected"
          style=""
          id="menuitem-tkdcd"
          role="option"
          aria-selected="true"
          aria-disabled="false"
          tabindex="0"
        >
          <svg
            class="spectrum-Icon spectrum-UIIcon-Checkmark300 spectrum-Icon--medium spectrum-Menu-itemIcon spectrum-Menu-checkmark"
            focusable="false"
            aria-hidden="true"
            role="img"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 14 14"
          >
            <path
              d="M5.102 12.514a1.09 1.09 0 0 1-.834-.39L.988 8.19A1.085 1.085 0 0 1 2.656 6.8l2.421 2.906 6.243-7.947a1.085 1.085 0 0 1 1.707 1.34L5.955 12.1a1.09 1.09 0 0 1-.838.415z"
            ></path>
          </svg>

          <span class="spectrum-Menu-itemLabel">Ballard</span>
        </li>

        <li
          class="spectrum-Menu-item"
          style=""
          id="menuitem-bkoh3"
          role="option"
          aria-selected="false"
          aria-disabled="false"
          tabindex="0"
        >
          <span class="spectrum-Menu-itemLabel">Fremont</span>
        </li>

        <li
          class="spectrum-Menu-item"
          style=""
          id="menuitem-oxbdi"
          role="option"
          aria-selected="false"
          aria-disabled="false"
          tabindex="0"
        >
          <span class="spectrum-Menu-itemLabel">Greenwood</span>
        </li>
        <div
          role="separator"
          class="spectrum-Divider spectrum-Divider--sizeS spectrum-Menu-divider"
          style=""
        ></div>
        <li
          class="spectrum-Menu-item is-disabled"
          style=""
          id="menuitem-iyjld"
          role="option"
          aria-selected="false"
          aria-disabled="true"
        >
          <span class="spectrum-Menu-itemLabel">United States of America</span>
        </li>
      </ul>
    </div>
  </div>
</template>
