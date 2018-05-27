Die goldenen Regeln für Texte im Internet

Zentrale Botschaft zu Beginn
Absätze und Zwischentitel nutzen
Anschaulich, aktiv und einfach schreiben
Texte mit Bildern, Videos, Links, etc. anreichern
Texte für Suchmaschinen optimieren, aber für Besucher schreiben
Texte und Webseiten weiterentwickeln und optimieren
Der Inhalt ist präzise, objektiv und fair

## Figure
{% include figure image_path="/assets/images/unsplash-image-10.jpg" alt="this is a placeholder image" caption="This is a figure caption." %}

## Gallery
gallery:
  - url: /assets/images/unsplash-gallery-image-1.jpg
    image_path: /assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"
  - url: /assets/images/unsplash-gallery-image-2.jpg
    image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Image 2 title caption"

{% include gallery caption="This is a sample gallery with **Markdown support**." %}

## Feature Row
feature_row:
  - image_path: /assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--inverse"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."

{% include feature_row %}