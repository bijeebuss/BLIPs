# BLIPs

Bloom Improvement Proposals (BLIPs) describe standards for the Bloom protocol including new functionality, specifications, and contract standards.

## Contributing

 1. Fork the repository by clicking "Fork" in the top right.
 2. Add your BLIP to your fork of the repository. There is a [template BLIP here](blip-template.md).
 3. Submit a Pull Request to Bloom's [BLIP repository](https://github.com/hellobloom/BLIPs).

Your first PR should be a first draft of the final BLIP. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new BLIP and assign it a number before merging it. Make sure you include a `discussions-to` header with the URL to a discussion forum or open GitHub issue where people can discuss the BLIP as a whole.

If your BLIP requires images, the image files should be included in a subdirectory of the `assets` folder for that BLIP as follow: `assets/blip-X` (for blip **X**). When linking to an image in the BLIP, use relative links such as `../assets/blip-X/image.png`.

Once your first PR is merged, we have a bot that helps out by automatically merging PRs to draft BLIPs. For this to work, it has to be able to tell that you own the draft being edited. Make sure that the 'author' line of your BLIP contains either your Github username or your email address inside <triangular brackets>. If you use your email address, that address must be the one publicly shown on [your GitHub profile](https://github.com/settings/profile).

When you believe your BLIP is mature and ready to progress past the draft phase, you should open a PR changing the state of your BLIP to 'Final'. An editor will review your draft and ask if anyone objects to its being finalised. If the editor decides there is no rough consensus - for instance, because contributors point out significant issues with the BLIP - they may close the PR and request that you fix the issues in the draft before trying again.

## BLIP Status Terms
* **Draft** - a BLIP that is undergoing rapid iteration and changes.
* **Last Call** - a BLIP that is done with its initial iteration and ready for review by a wide audience.
* **Accepted** - a core BLIP that has been in Last Call for at least 2 weeks and any technical changes that were requested have been addressed by the author.
* **Final** - a BLIP that has been in Last Call for at least 2 weeks and any technical changes that were requested have been addressed by the author.
* **Deferred** - a BLIP that is not being considered for immediate adoption. May be reconsidered in the future for a subsequent hard fork.

# Credit

Based on the model and templates put forth for [Ethereum Improvement Proposals](https://github.com/ethereum/EIPs).
