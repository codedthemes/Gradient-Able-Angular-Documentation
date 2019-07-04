---
description: Menu/Layout Customize Options
---

# Theme Configuration

{% hint style="info" %}
You can edit this file at **`[ ../src/app/app-config.ts ]`**
{% endhint %}

| **Option** | **Default** | **Data Type** | **Description** |
| :--- | :--- | :--- | :--- |
| **layout** | vertical | String | `vertical`, `horizontal` |
| **subLayout** | - | String | `horizontal-2` \(only used for layout is horizontal\) |
| **collapseMenu** | false | Boolean | `true`, `false` |
| **layoutType** | menu-dark | String | `menu-dark`, `menu-light`, `dark` |
| **headerBackColor** | header-blue | String | `header-blue`, `header-red`, `header-purple`, `header-info`, `header-dark`, `header-orenge`, `header-green`, `header-yellow`, `header-orchidgreen`, `header-indigogreen`, `header-darkgreen`, `header-darkblue` |
| **rtlLayout** | false | Boolean | `true`, `false` |
| **navFixedLayout** | true | Boolean | `true`, `false` |
| **headerFixedLayout** | true | Boolean | `true`, `false` |
| **boxLayout** | false | Boolean | `true`, `false` |

{% code-tabs %}
{% code-tabs-item title="app-config.ts" %}
```javascript
export class GradientConfig {
  public static config = {
    layout: 'vertical', // vertical, horizontal
    subLayout: '', // horizontal-2
    collapseMenu: false,
    layoutType: 'menu-light', // menu-dark, menu-light, dark
    headerBackColor: 'header-blue', // header-default, header-blue, header-red, header-purple, header-info, header-dark
    // header-green, header-yellow, header-orchidgreen, header-indigogreen, header-darkgreen, header-darkblue
    rtlLayout: false,
    navFixedLayout: true,
    headerFixedLayout: true,
    boxLayout: false,
  };
}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

