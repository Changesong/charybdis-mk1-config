# Symbol Frequency Analysis for Keyboard Layout Optimization

## C Language Symbol Frequency

Source: External corpus analysis

| Symbol | Frequency % |
|--------|-------------|
| `_` | 2.550 |
| `*` | 1.769 |
| `,` | 1.565 |
| `.` | 1.512 |
| `)` | 1.373 |
| `(` | 1.372 |
| `;` | 1.276 |
| `-` | 1.176 |
| `=` | 1.039 |
| `/` | 0.718 |
| `>` | 0.587 |
| `"` | 0.376 |
| `{` | 0.303 |
| `&` | 0.237 |
| `}` | 0.210 |
| `:` | 0.192 |
| `+` | 0.182 |
| `#` | 0.175 |
| `]` | 0.163 |
| `[` | 0.163 |
| `<` | 0.118 |
| `%` | 0.105 |
| `!` | 0.102 |
| `'` | 0.101 |
| `\|` | 0.098 |
| `?` | 0.022 |
| `@` | 0.009 |
| `$` | 0.005 |
| `^` | 0.003 |
| `~` | 0.002 |

## Rust Language Symbol Frequency

Source: Analysis of ~26,000 characters of idiomatic Rust code including lexer implementation, AST definitions, trait implementations, generics, closures, and iterator patterns.

| Symbol | Count | Frequency % |
|--------|-------|-------------|
| `,` | 569 | 2.151 |
| `(` | 517 | 1.954 |
| `)` | 517 | 1.954 |
| `:` | 512 | 1.935 |
| `.` | 302 | 1.142 |
| `>` | 243 | 0.919 |
| `'` | 236 | 0.892 |
| `=` | 226 | 0.854 |
| `{` | 209 | 0.790 |
| `}` | 209 | 0.790 |
| `_` | 202 | 0.764 |
| `;` | 140 | 0.529 |
| `/` | 122 | 0.461 |
| `<` | 117 | 0.442 |
| `"` | 114 | 0.431 |
| `\|` | 100 | 0.378 |
| `-` | 39 | 0.147 |
| `#` | 33 | 0.125 |
| `[` | 33 | 0.125 |
| `]` | 33 | 0.125 |
| `+` | 27 | 0.102 |
| `!` | 27 | 0.102 |
| `*` | 14 | 0.053 |
| `?` | 14 | 0.053 |
| `%` | 4 | 0.015 |
| `^` | 3 | 0.011 |
| `\` | 3 | 0.011 |
| `@` | 1 | 0.004 |

## Comparison: Rust vs C

| Symbol | C % | Rust % | Difference | Reason |
|--------|-----|--------|------------|--------|
| `:` | 0.192 | 1.935 | **+1.743** | Type annotations everywhere in Rust |
| `'` | 0.101 | 0.892 | **+0.791** | Lifetimes (`'a`, `'static`) |
| `,` | 1.565 | 2.151 | +0.586 | More generics, tuple usage |
| `(` | 1.372 | 1.954 | +0.582 | More functional patterns |
| `)` | 1.373 | 1.954 | +0.581 | |
| `}` | 0.210 | 0.790 | +0.580 | More blocks (match, closures) |
| `{` | 0.303 | 0.790 | +0.487 | |
| `>` | 0.587 | 0.919 | +0.332 | Generics, return type arrows |
| `<` | 0.118 | 0.442 | +0.324 | Generics |
| `\|` | 0.098 | 0.378 | +0.280 | Closures, pattern matching |
| `"` | 0.376 | 0.431 | +0.055 | Similar usage |
| `?` | 0.022 | 0.053 | +0.031 | Error propagation operator |
| `!` | 0.102 | 0.102 | 0.000 | Macros vs negation |
| `[` | 0.163 | 0.125 | -0.038 | |
| `]` | 0.163 | 0.125 | -0.038 | |
| `#` | 0.175 | 0.125 | -0.050 | Attributes vs preprocessor |
| `+` | 0.182 | 0.102 | -0.080 | Less pointer arithmetic |
| `%` | 0.105 | 0.015 | -0.090 | Less formatting |
| `=` | 1.039 | 0.854 | -0.185 | |
| `&` | 0.237 | ~0.3* | ~+0.06 | References (comparable) |
| `/` | 0.718 | 0.461 | -0.257 | |
| `.` | 1.512 | 1.142 | -0.370 | |
| `;` | 1.276 | 0.529 | **-0.747** | Rust expressions don't need `;` |
| `-` | 1.176 | 0.147 | **-1.029** | No pointer arithmetic |
| `*` | 1.769 | 0.053 | **-1.716** | No raw pointers in safe Rust |
| `_` | 2.550 | 0.764 | **-1.786** | Still used but less dominant |

*Note: `&` was underrepresented in Rust analysis due to sampling

## Go Language Symbol Frequency

Source: Analysis of ~16,000 characters of idiomatic Go code including HTTP handlers, interfaces, generics, goroutines, channels, worker pools, and file I/O patterns.

| Symbol | Count | Frequency % |
|--------|-------|-------------|
| `.` | 272 | 1.670 |
| `(` | 262 | 1.608 |
| `)` | 262 | 1.608 |
| `,` | 251 | 1.541 |
| `"` | 180 | 1.105 |
| `:` | 161 | 0.988 |
| `=` | 154 | 0.945 |
| `{` | 144 | 0.884 |
| `}` | 144 | 0.884 |
| `/` | 133 | 0.816 |
| `*` | 58 | 0.356 |
| `[` | 51 | 0.313 |
| `]` | 51 | 0.313 |
| `` ` `` | 42 | 0.258 |
| `%` | 39 | 0.239 |
| `!` | 28 | 0.172 |
| `<` | 25 | 0.153 |
| `&` | 24 | 0.147 |
| `_` | 21 | 0.129 |
| `;` | 20 | 0.123 |
| `-` | 15 | 0.092 |
| `+` | 10 | 0.061 |
| `\|` | 7 | 0.043 |
| `>` | 3 | 0.018 |

## Comparison: Go vs C

| Symbol | C % | Go % | Difference | Reason |
|--------|-----|------|------------|--------|
| `:` | 0.192 | 0.988 | **+0.796** | Short variable declarations `:=` |
| `"` | 0.376 | 1.105 | **+0.729** | More string literals, struct tags |
| `}` | 0.210 | 0.884 | **+0.674** | Mandatory braces for all blocks |
| `{` | 0.303 | 0.884 | **+0.581** | |
| `` ` `` | 0.000 | 0.258 | **+0.258** | Raw strings, struct tags |
| `(` | 1.372 | 1.608 | +0.236 | |
| `)` | 1.373 | 1.608 | +0.235 | |
| `.` | 1.512 | 1.670 | +0.158 | Method calls, package access |
| `[` | 0.163 | 0.313 | +0.150 | Slices, maps |
| `]` | 0.163 | 0.313 | +0.150 | |
| `%` | 0.105 | 0.239 | +0.134 | fmt.Printf formatting |
| `/` | 0.718 | 0.816 | +0.098 | Import paths |
| `!` | 0.102 | 0.172 | +0.070 | Error checking `!= nil` |
| `<` | 0.118 | 0.153 | +0.035 | Generics, channels |
| `,` | 1.565 | 1.541 | -0.024 | Similar |
| `\|` | 0.098 | 0.043 | -0.055 | Less common (no pattern matching) |
| `&` | 0.237 | 0.147 | -0.090 | Address-of operator |
| `=` | 1.039 | 0.945 | -0.094 | `:=` replaces many `=` |
| `'` | 0.101 | 0.006 | **-0.095** | Rare (only rune literals) |
| `+` | 0.182 | 0.061 | -0.121 | |
| `#` | 0.175 | 0.000 | **-0.175** | No preprocessor |
| `>` | 0.587 | 0.018 | **-0.569** | Channels use `<-` not `>` |
| `-` | 1.176 | 0.092 | **-1.084** | No pointer arithmetic |
| `;` | 1.276 | 0.123 | **-1.153** | Automatic semicolon insertion |
| `*` | 1.769 | 0.356 | **-1.413** | Pointers less common than C |
| `_` | 2.550 | 0.129 | **-2.421** | CamelCase convention |

## Key Differences: All Three Languages

### Symbols MORE important in Rust than C:
- **`:`** - Critical for type annotations (10x more frequent)
- **`'`** - Lifetimes are unique to Rust (9x more frequent)
- **`|`** - Closures `|x| x + 1` and pattern matching (4x more frequent)
- **`<>`** - Generics everywhere (3x more frequent)
- **`{}`** - More block expressions (3x more frequent)
- **`?`** - Error propagation operator

### Symbols MORE important in C than Rust:
- **`*`** - Pointers everywhere (33x more frequent)
- **`_`** - Snake_case plus macro conventions (3x more frequent)
- **`-`** - Pointer arithmetic, `->` operator (8x more frequent)
- **`;`** - Every statement needs one (2x more frequent)
- **`#`** - Preprocessor directives

### Symbols MORE important in Go than C:
- **`"`** - String literals, struct tags (3x more frequent)
- **`:`** - Short declarations `:=` (5x more frequent)
- **`{}`** - Mandatory braces for all blocks (3x more frequent)
- **`` ` ``** - Raw strings, struct tags (unique to Go)
- **`[]`** - Slices are fundamental (2x more frequent)
- **`%`** - Printf formatting (2x more frequent)

### Symbols MORE important in C than Go:
- **`_`** - CamelCase replaces snake_case (20x more frequent in C)
- **`*`** - Fewer raw pointers (5x more frequent in C)
- **`;`** - Automatic insertion in Go (10x more frequent in C)
- **`-`** - No pointer arithmetic (13x more frequent in C)
- **`>`** - Channels use `<-` not `>` (33x more frequent in C)

### Unique to each language:
- **C**: `#` preprocessor, `->` pointer member access
- **Rust**: `'` lifetimes, `?` error propagation, `|` closures
- **Go**: `` ` `` raw strings/struct tags, `<-` channel operator

## Layout Recommendations

### For C-focused development:
Priority placement: `_` `*` `()` `;` `-` `=`

### For Rust-focused development:
Priority placement: `()` `:` `'` `<>` `{}` `|`

### For Go-focused development:
Priority placement: `.` `()` `"` `:` `=` `{}` `[]` `` ` ``

### For mixed C/Rust/Go development:
Priority placement: `()` `{}` `:` `=` `.` `"` `,` `[]`

## Summary Table: Top 10 by Language

| Rank | C | Rust | Go |
|------|---|------|-----|
| 1 | `_` 2.55% | `,` 2.15% | `.` 1.67% |
| 2 | `*` 1.77% | `()` 1.95% | `()` 1.61% |
| 3 | `,` 1.57% | `:` 1.94% | `,` 1.54% |
| 4 | `.` 1.51% | `.` 1.14% | `"` 1.11% |
| 5 | `()` 1.37% | `>` 0.92% | `:` 0.99% |
| 6 | `;` 1.28% | `'` 0.89% | `=` 0.95% |
| 7 | `-` 1.18% | `=` 0.85% | `{}` 0.88% |
| 8 | `=` 1.04% | `{}` 0.79% | `/` 0.82% |
| 9 | `/` 0.72% | `_` 0.76% | `*` 0.36% |
| 10 | `>` 0.59% | `;` 0.53% | `[]` 0.31% |
