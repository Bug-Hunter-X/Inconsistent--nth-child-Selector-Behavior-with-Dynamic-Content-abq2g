# Inconsistent :nth-child Selector Behavior with Dynamic Content

This repository demonstrates a common issue encountered when using the CSS `:nth-child` selector with dynamically added elements. The `:nth-child` selector does not update automatically when new elements are added to the DOM after initial page load. This can lead to unexpected styling and layout issues.

**Bug:** The example CSS styles every other list item. However, when new items are added dynamically, the styling does not correctly apply to the new items.

**Solution:** Instead of relying on `:nth-child`, consider using JavaScript to apply the styling based on the element's index in the updated DOM.