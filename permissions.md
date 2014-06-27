# `<permissions>`

Article permissions: copyright details, license URL, license text.

## PeerJ

```xml
<permissions>
  <copyright-statement>© 2014 Surname et al.</copyright-statement>
  <copyright-year>2014</copyright-year>
  <copyright-holder>Surname et al.</copyright-holder>
  <license license-type="open-access" xlink:href="http://creativecommons.org/licenses/by/4.0/">
    <license-p>This is an open access article distributed under the terms of the <ext-link ext-link-type="uri" xlink:href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution License</ext-link>, which permits unrestricted use, distribution, reproduction and adaptation in any medium and for any purpose provided that it is properly attributed. For attribution, the original author(s), title, publication source (PeerJ) and either DOI or URL of the article must be cited.</license-p>
  </license>
</permissions>
```

## eLife

```xml

<permissions>
                <copyright-statement>Copyright &#xa9; 2012, Alegado et al</copyright-statement>
                <copyright-year>2012</copyright-year>
                <copyright-holder>Alegado et al</copyright-holder>
                <license license-type="open-access" xlink:href="http://creativecommons.org/licenses/by/4.0/">
                    <license-p>This article is distributed under the terms of the <ext-link ext-link-type= "uri" xlink:href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution License</ext-link>, which permits unrestricted use and redistribution provided that the original author and source are credited.</license-p>
                </license>
            </permissions>
```

## PMC Tagging Guidelines examples

#### Multiple License Types

```xml
<permissions>
  <copyright-statement>Copyright &#xA9; 2012 Medical
    Publishing Corp.</copyright-statement>
  <copyright-year>2012</copyright-year>
  <license license-type="open-access"
    xlink:href="http://creativecommons.org/licenses/by-nc/3.0/">
    <license-p>This article is distributed under the terms of the
      Creative Commons Attribution Non-Commercial License, which permits
      unrestricted non-commercial use, distribution, and reproduction in any 
      medium, provided the original work is properly cited.</license-p>
  </license>
  <license license-type="ccc">
    <license-p>For permission to reuse copyrighted content from this publication, 
      please go to <ext-link ext-link-type="uri" 
      xlink:href="http://www.copyright.com">www.copyright.com</ext-link>, or 
      contact Copyright Clearance Center, 222 Rosewood Drive, Danvers, MA 01923</license-p>
  </license>
</permissions>
````

#### License with URI in the license text

```xml
<license license-type="open-access">
  <license-p>This article is distributed under the terms of the Creative Commons Attribution License 
    (<ext-link ext-link-type="uri" xlink:href="http://creativecommons.org/licenses/by/3.0/">
    http://creativecommons.org/licenses/by/3.0/</ext-link>), which permits unrestricted use and 
    redistribution provided that the original author and source are credited.</license-p>
</license>
````
#### License with URI not in the license text

```xml
<license license-type="open-access" xlink:href="http://creativecommons.org/licenses/by/3.0/">
  <license-p>This article is distributed under the terms of the Creative Commons Attribution License, 
  which permits unrestricted use and redistribution provided that the original author and 
  source are credited.</license-p>
</license>
````









