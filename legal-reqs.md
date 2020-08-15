# Legal Requirements when Contributing Code to Jolocom

---
How to make sure your code contributions can be included in the jolocom-lib and jolocom-sdk codebases.
---

## Jolocom Software Licensing

The Jolocom repositories jolocom-lib and jolocom-sdk are licensed under an [Apache 2.0 license](https://www.apache.org/licenses/LICENSE-2.0.html). This page describes the Jolocom policy to ensure that all contributions to the jolocom-lib and jolocom-sdk code are also licensed under the Apache 2.0 license (and that the contributor has the right to license it as such).

If you are:

- a _current_ employee of Jolocom GmbH

then there is nothing extra for you to do: licensing is already handled.

Otherwise you are an "external contributor" and you must do the following:

1. Make sure that every file you modified or created contains a copyright notice comment like the following (at the top of the file):

   ```text
   # Copyright Jolocom GmbH and Jolocom contributors
   # SPDX-License-Identifier: (Apache-2.0 AND CC-BY-4.0)
   # Code is Apache-2.0 and docs are CC-BY-4.0
   ```

   - If a copyright notice is not present, then add one.
   - If the first line of the file is a line beginning with `#!` (e.g. `#!/usr/bin/python3`) then leave that as the first line and add the copyright notice afterwards.
   - If a copyright notice is present but it says something like `Copyright 2019 Jolocom GmbH` then please change it to say the above.
   - Make sure you're using the correct syntax for comments (which varies from language to language). The example shown above is for a Python file.

1. Read the [Developer Certificate of Origin, Version 1.1](https://developercertificate.org/).
1. You will be asked to include a Signed-off-by line in all your commit messages. (Instructions are given in the next step.) Make sure you understand that including a Signed-off-by line in your commits certifies that you can make the statements in the Developer Certificate of Origin. If you have questions about this, then please [ask on Gitter](https://gitter.im/jolocom/SmartWallet) or elsewhere. Do not continue until you fully understand.
1. Make sure that all your commit messages include a Signed-off-by line of the form:

   ```text
   Signed-off-by: Random J Developer <random@developer.example.org>
   ```

   with your real name and your real email address. Sorry, no pseudonyms or anonymous contributions. Tip: You can tell Git to include a Signed-off-by line in a commit message by using `git commit --signoff` or `git commit -s`.

## Credits

The Developer Certificate of Origin was developed by the Linux community and has since been adopted by other projects, including many under the Linux Foundation umbrella (e.g. Hyperledger Fabric).
The process described above (with the Signed-off-by line in Git commits) is also based on [the process used by the Linux community](https://github.com/torvalds/linux/blob/master/Documentation/process/submitting-patches.rst#11-sign-your-work---the-developers-certificate-of-origin).
