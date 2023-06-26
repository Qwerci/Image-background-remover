# Image-background-remover

Project description

Build an image background remover model and serve it through an API.

Requirements

    Model specification
        The input will be an image in png or jpg format, in BGR of any size
        The output will b a BGRA image in png format, same size as the original image with its fourth channel set to 0 in all pixels where the background was removed.
        The model will be optimized in the case of a single person, full body and/or in front of a background with no other person 
        It is preferrable to build a modle without collecting and annotating custom data.
    

    Deliverables
        API endpoints
        Basic documentation on how to interact with the API
        Documentation on how to retrain the model.
