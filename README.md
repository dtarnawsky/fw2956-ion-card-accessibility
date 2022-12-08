# ion-card Accessibility

A problem with `ion-card` where the usage of href set the role of the card to be a button (an improvement added in v6) however, clicking on the card opened a new page so the correct role should be link. 

The suggested improvement would be a way to set the role of an ion-card programmatically.