## Support materials for workshop

Use this page to copy/paste information and save you from the typo gremlin.


**CLAUDE.md**

```
# ALWAYS FOLLOW
- Use Python 3.12 for ALL code
- Use uv for all package and dependency management
```


**SKILL.md**

---
name: spdx-headers
description: Use when a source file is missing its SPDX license header, or when asked to add license headers across a codebase.
allowed-tools: Read Edit Glob
model: haiku
---

## Steps

1. Detect the file's language from its extension.
2. Check if a header already exists — skip if so.
3. Insert the correct SPDX-License-Identifier comment at the top.
4. Use the license defined in LICENSE at the project root.
5. If no Open Source licence exists using the following

```
Minimal header

# SPDX-FileCopyrightText: 2026 Beachgeek Corp
# SPDX-License-Identifier: LicenseRef-Beachgeek-Commercial

Fuller version

# SPDX-FileCopyrightText: 2026 Beachgeek Corp <legal@beachgeek.org>
# SPDX-License-Identifier: LicenseRef-Beachgeek-Commercial-1.0
#
# Proprietary and confidential. Unauthorized copying, distribution, or
# modification of this file, via any medium, is strictly prohibited
# without a valid commercial licence from Beachgeek Corp.
```


**MIT License**

```
MIT License

Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
