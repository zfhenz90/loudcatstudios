# loudcatstudios.com

The company site for Loud Cat Studios, served by GitHub Pages from `main`. It is a single static
page with no build step: edit `index.html` and push.

Its main job is to be the public, working website on the organization's own domain that Apple's
organization enrollment requires. Apple rejects registrar placeholder pages and sites with minimal
content, so keep it real rather than a stub.

- `CNAME` binds the Pages site to `loudcatstudios.com`. DNS lives at Porkbun: apex `A` records to
  GitHub Pages' addresses, and `www` as a `CNAME` to `zfhenz90.github.io`.
- The contact address relies on email forwarding configured at the registrar, not on anything here.
- Once the Farwatch privacy policy is published, link it from the product card.
