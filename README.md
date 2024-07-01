# mesop svg_icon web component

This is a [Mesop](https://google.github.io/mesop/) web_component implementation to provide an SVG icon.

## Usage

import the component

```
from svg_icon.svg_icon_component import (
    svg_icon,
)
```

use the component with a full `<svg> ... </svg>` element in a mesop.Page

```
 svg_icon(svg="""<svg data-icon-name="exampleIcon" .... </svg>""")
```

## Examples

* `svg_icon_app.py` contains an example

* [colab example](https://colab.research.google.com/drive/1PNJnlNloIWEja_MDtDGQjhBu1OdI_aDU)


