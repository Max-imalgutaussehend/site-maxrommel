# site-maxrommel

The personal website (al-folio, built static output). CI builds a Caddy image from `site/`; the Aevia platform
deploys it by digest. To change the site: edit `site/`, push to `main`, take the digest from the job summary
into the platform's `catalog/services.yml`.
