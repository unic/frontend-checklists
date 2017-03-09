### This is a sample checklist based on previous experiences when developing Overlay component.
Please check if you know answers to at least questions below before starting implementation of Overlay component.


- [ ] Is there an overlay?

 - [ ] If so, is it clickable? And what should then happen?

- [ ] Is the height from the overlay fix?

- [ ] How is the overlay in small viewport? Full bleed? Full grid? Content width? Custom width? Full height? Content height? Custom height?

- [ ] How is the position of the overlay calculated? Center? Top?

- [ ] Is there a scroll foreseen?

 - [ ] If so, is there any element that should stay fix?

- [ ] Is there a closing button?

- [ ] Whare are the possibilities to close overlay? Button/Background click/Other component event trigger

- [ ] Is there keyboard support?

- [ ] Is there focus support?

- [ ] Is there accessibility support?

- [ ] Where is the content from the overlay coming from? DOM? AJAX? IFRAME?

- [ ] How should the overlay be triggered? Click on known element? Event based from any module? URL based?

- [ ] Is there a background covering rest of the page?

 - [ ] If so, is it clickable, what should happen when it's clicked? Closing opened overlay?

- [ ] Is there a possibility to open multiple overlays?

- [ ] Should the overlay be the topmost element when opened or there are any other modules coming in front?

- [ ] Should we care about scrolling background? Or Background scroll should be disabled?

- [ ] Are there show and hide animations?
