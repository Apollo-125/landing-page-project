# landing-page-project
The Landing Page project for TOP:Foundations.

This will be my first "project from scratch" on the course and I will list my rough thought-process here for the site creation. I am going to make a conscious decision
not to worry about 'best practice' in terms of laying this out, as this has caused frustration on previous assignments. As such, I will likely end up with more classes
than I probably need to, although none of them will be unused.

I will look to complete this by splitting the page into four main sections, and the header/footer. I will follow the advice from TOP and complete the HTML for each
section prior to going into the stylesheet, and working my way down.

The rough layout I am thinking will be similar to the below:

page-container/OR body

    header
        header-left
            header-logo
        header-right
            header-link-wrapper
                header-links


    banner-container
        banner-text
            (Will experiment to see if this can just be two div blocks, and the sign up will be a button/inline-block)
        banner-image

    information-container (Switch to flex-direction column)
        information-title
        information-box-grid
            information-box

    quotebox-container
        (Possibly do this with two div blocks with two text classes for style? Might not need to flex?)


    account-container
        (Perhaps here will use a wrapper, with two flex items, left containing div blocks for text and right a button?)

    footer
        (Straightforward footer)
