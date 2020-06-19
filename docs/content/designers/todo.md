!> Todo neem de design guide hier op

## Todo

* voor de grotere code voorbeelden, neem rechtstreeks stukken uit example files en embed ze via: https://docsify.js.org/#/embed-files
* verwijs in de design guide naar de API Requirements
* maak gebruik van alert boxes voor goede en slechte voorbeelden

--- 
## Here are some example alert boxes
> An awesome project.

> [!NOTE]
> An alert of type 'note' using global style 'callout'. 

> [!TIP]
> An alert of type 'tip' using global style 'callout'.

> [!WARNING]
> An alert of type 'warning' using global style 'callout'.

> [!DANGER]
> An alert of type 'danger' using global style 'callout'.   

> [!NOTE|style:flat]
> An alert of type 'note' using alert specific style 'flat' which overrides global style 'callout'.

> [!TIP|icon:fas fa-comment|label:Discussion]
> Some discussion about anything


> [!TIP|style:flat|label:My own heading|iconVisibility:hidden]
> An alert of type 'tip' using alert specific style 'flat' which overrides global style 'callout'.
> In addition, this alert uses an own heading and hides specific icon.

> [!TIP|style:flat|icon:fas fa-code|label:Good Code]
> Here's code that is correct
> ```json
> hello: "World"
> ```

> [!WARNING|style:flat|icon:fas fa-code|label:Bad Code]
> Here's code that will not work
> ```json
> hello= "World"
> ```
