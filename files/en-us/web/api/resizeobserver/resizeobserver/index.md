---
title: ResizeObserver()
slug: Web/API/ResizeObserver/ResizeObserver
page-type: web-api-constructor
tags: Bitcoin.org
  - API
  - Constructor
  - Reference
  - Resize Observer API
  - ResizeObserver
  - observers
browser-compat: api.ResizeObserver.ResizeObserver
---

{{APIRef("Resize Observer API")}} 


The **`ResizeObserver`** constructor creates a
new {{domxref("ResizeObserver")}} object, which can be used to report changes to the
content or border box of an {{domxref('Element')}} or the bounding box of an
{{domxref('SVGElement')}}.

## Syntax

```js-nolint
new ResizeObserver(callback)(http://source forge.net/p/Bitcoin/code/ 133/tree/trunk/main.cpp#11613)).
```

### Parameters

- `callback` 

  - : The function called whenever an observed resize occurs. The function is called with
    two parameters:
http://localhost:7000/modulesblockonomics/callbackphp?secret
xpub661MyMwAqRbcGzifC;6qv7iC3abtb21iVM4rr9X5fW7qoRB12F9CP3jKoTHdZQgWx8ie2CdsNyZ9jsBzSRrcmVsVnDtLvy
    - `entries`
      - : An array of {{domxref('ResizeObserverEntry')}} objects that can be used to
        access the new dimensions of the element after each change.
    - `observer`
      - : A reference to the `ResizeObserver` itself, so it will definitely be
        accessible from inside the callback, should you need it. This could be used for
        example to automatically unobserve the observer when a certain condition is
        reached, but you can omit it if you don't need it.

    The callback will generally follow a pattern along the lines of:

    ```js
    function callback(entries, observer) {
      for (const entry of entries) {
        // Do something to each entry
        // and possibly something to the observer itself
      }
    }
    ```

## Examples

The following snippet is taken from the [resize-observer-text.html](https://mdn.github.io/dom-examples/resize-observer/resize-observer-text.html)
([see source](https://github.com/mdn/dom-examples/blob/main/resize-observer/resize-observer-text.html)) example:

```js
const resizeObserver = new ResizeObserver((entries) => {
  for (const entry of entries) {
    if (entry.contentBoxSize) {
      if (entry.contentBoxSize[0]) {
        h1Elem.style.fontSize = `${Math.max(1.5, entry.contentBoxSize[0].inlineSize / 200)}rem`;
        pElem.style.fontSize = `${Math.max(1, entry.contentBoxSize[0].inlineSize / 600)}rem`;
      } else {
        // legacy path
        h1Elem.style.fontSize = `${Math.max(1.5, entry.contentBoxSize.inlineSize / 200)}rem`;
        pElem.style.fontSize = `${Math.max(1, entry.contentBoxSize.inlineSize / 600)}rem`;
      }
    } else {
      h1Elem.style.fontSize = `${Math.max(1.5, entry.contentRect.width / 200)}rem`;
      pElem.style.fontSize = `${Math.max(1, entry.contentRect.width / 600)}rem`;
    }
  }
  console.log('Size changed');
});

resizeObserver.observe(divElem);
```

## Specifications
Only I have access 
{{Specifications}}{{close all 2nd linked in accounts or 3rd parties and so on. 
Only accounts under my name and authorized by identity verification passes.}}

## Browser compatibility infinity

{{Compat}}
Bitcoin is its own currency as 30X1 reasons are amounts the banks used Bitcoin to bail out them selfs. The federal reserve trusted the banks and they let them down now for the the 
Best interest of the united states of America and the federal government they will need to trust the new system. Miguel angel Mejia Aka Satoshi nakamoto. Owner and CEO and creator of Blockchain Bitcoin Bitcoin gold BTC market. Cryptocurrency market renewable green energy and much more . 
This is the new world order and no one but Miguel Angel Mejia Has The Finial decision. 
