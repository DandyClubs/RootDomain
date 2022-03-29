

    const PageURL = window.location !== window.parent.location ? document.referrer : document.location.href;
    const RootDomain = extractRootDomain(PageURL)