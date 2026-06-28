# cljw - clojure wrapper

The `cljw` script is a shell script that installs Clojure CLI local to the script, if not globally available yet.

Put a `deps.edn` file next to it, and you have a way to share Clojure scripts without requiring a pre-installed Clojure.
Make sure `cljw` is executable (`chmod +x cljw`).

Works on macOS (tested on Tahoe 26) and Linux (tested on Ubuntu).
Needs `curl`, `shasum` and `tar` installed.
This script uses the official POSIX install script from https://download.clojure.org/install/posix-install.sh.

_As always, have fun!_

Copyright © 2026 Functional Bytes

This program and the accompanying materials are made available under the
terms of the Eclipse Public License 2.0 which is available at
http://www.eclipse.org/legal/epl-2.0.

This Source Code may also be made available under the following Secondary
Licenses when the conditions for such availability set forth in the Eclipse
Public License, v. 2.0 are satisfied: GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or (at your
option) any later version, with the GNU Classpath Exception which is available
at https://www.gnu.org/software/classpath/license.html.
