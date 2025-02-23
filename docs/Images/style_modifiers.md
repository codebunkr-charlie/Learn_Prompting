---
sidebar_position: 4
---
# 🟢 Style Modifiers

Style modifiers are simply descriptors which consistently
produce certain styles (e.g. 'tinted red', 'made of glass', 'rendered in Unity')(@oppenlaender2022taxonomy). They can be combined together to
produce even more specific styles. They can "include information about art periods, schools, and styles, but also art materials and media, techniques, and artists"(@oppenlaender2022taxonomy).

import pyramids from '../assets/images_chapter/pyramids.png';
import red_pyramids from '../assets/images_chapter/red_pyramids.png';

# Example

Here are a few pyramids generated by DALLE, with the prompt `pyramid`.

<div style={{textAlign: 'center'}}>
  <img src={pyramids} style={{width: "750px"}} />
</div>

Here are a few pyramids generated by DALLE, with the prompt `A pyramid made of glass, rendered in Unity and tinted red`, which uses 3 style modifiers.

<div style={{textAlign: 'center'}}>
  <img src={red_pyramids} style={{width: "750px"}} />
</div>

## Notes

Oppenlaender et al.(@oppenlaender2022taxonomy) describe the `rendered in ...` descriptor 
as a quality booster, but our working definition differs, since that modifier does consistently generate the specific Unity (or other render engine) style. As such, we will call that descriptor a style modifier.