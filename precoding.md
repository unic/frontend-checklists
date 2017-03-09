# Pre coding

## Design

- [ ] Do I have designs for every breakpoint?
	- If not, can I come up myself with a proposal for it? Probably sketching it with pen and paper would be enough.

- [ ] Do I have all icons? Do I have them in the proper format?

- [ ] Do I have all colors from the module in the frontend configuration and style guide?

- [ ] If the mobile design starts from 375px width - double check if we shouldn't support lower viewports - like still popular iPhone5 - 320px

## Content model

- [ ] Do I have all images? In their size(s)?

- [ ] Do I have all necessary elements defined?
	- Do I know if they are all mandatory?
	- Do I have designs for variants where non-mandatory content elements are missing?
	- If not, can I come up myself with a proposal for it? Probably sketching it with pen and paper would be enough.
 
- [ ] Can I preview what would happen if the content (of a part) of a module changes? Specially in size/length. Ex:
	- What happens if the text of the link(s)/navigation element(s) is longer/shorter?
	- What happens if the paragraph text or the list is longer/shorter?
	- What happens if the provided image is portrait/landscape/square? (if that is not constrained by specs)
 
- [ ] Should the Component be localised?

## About Styles

- [ ] Is it possible to imagine what will happen with the module when I expand/shrink the viewport? Is my imagined result something covered by designs?

- [ ] Is it possible to preview other in between steps a part from the device breakpoints?

## JavaScript

- [ ] Is the module requiring JS?
	- Sure it cannot be achieved without?
	- Would using `input[type=radio]` or `input[type=checkbox]` together with adjacent (`~`) and target (`:target`) selectors solve it?

- [ ] Is the module requiring external libraries or plugins?
	- Are they still maintained?
	- Is there something newer (and more important, better) that covers the needs of the module?
	- Do they have a licensing model that we can use?
	- Do we have experience implementing them from previous projects?

- [ ] What are options acceptable by the module?
	- Are any of those options mandatory?
 
- [ ] Are there any dynamically generated elements that might need translation?

- [ ] External Libraries
	- Do I need the whole functionality that library is offering or only a small subset? Maybe it's possible to import only part of it, (for example - lodash merge, vs whole lodash lib)
