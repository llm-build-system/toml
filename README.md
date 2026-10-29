# toml++ - llm port

Original project: [toml++](https://github.com/marzer/tomlplusplus), version 3.4.0.
Original author: [Mark Gillard](https://github.com/marzer), with contributions
from the upstream community. [Original repository](https://github.com/marzer/tomlplusplus).

The library is the work of its original authors, not a product of llm-build-system.
This repository only maintains its llm build integration and header subset.
It is not an official upstream release. All headers and their directory structure
are unchanged. Upstream build files, tools and documentation are omitted.

The original license is preserved verbatim in [LICENSE](LICENSE).
[Upstream license](https://github.com/marzer/tomlplusplus/blob/v3.4.0/LICENSE).

Additional upstream copyright and license notices from the included source
files are reproduced verbatim in [NOTICE](NOTICE) for binary redistribution.
The original notices remain in the source files.

Consumers use `#include <toml++/toml.hpp>` with C++17 or newer.
No compiled library, generator or external dependency is required.
