---
title: "Home"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/thailandbeach.jpg?nf_resize=fit&w=1200
excerpt: "InfoSec, Privacy, Cloud Computing and more..."
# intro: 
#   - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin.'
feature_row:
  - image_path: assets/images/wildpacific.jpg?nf_resize=fit&w=400
    alt: "Wild Pacific Trail"
    title: "Information Security"
    excerpt: ""
  - image_path: /assets/images/saintmariesurmer.jpg?nf_resize=fit&w=400
    alt: "Saint Marie sur Mer"
    title: "Privacy"
    excerpt: ""
  - image_path: /assets/images/cliffsofmoher.jpg?nf_resize=fit&w=400
    alt: "Cliffs of Moher"
    title: "Cloud Computing"
    excerpt: ""
---
<script src="https://identity.netlify.com/v1/netlify-identity-widget.js"></script>

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

<script>
  if (window.netlifyIdentity) {
    window.netlifyIdentity.on("init", user => {
      if (!user) {
        window.netlifyIdentity.on("login", () => {
          document.location.href = "/admin/";
        });
      }
    });
  }
</script>