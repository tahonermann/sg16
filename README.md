# WG21 SG16 Unicode study group
SG16 is an ISO/IEC JTC1/SC22/WG21 C++ study group tasked with improving Unicode and text processing support within the C++ standard.

If you would like to contribute to the discussion, please subcribe to our mailing list at
https://lists.isocpp.org/mailman/listinfo.cgi/sg16.

Meetings are generally held twice a month; invitations are sent to the mailing list.
Summaries of past meetings are available at
https://github.com/sg16-unicode/sg16-meetings/blob/master/README.md.

A standing paper that describes our intended scope, directives, guidelines and
constraints is available at [P1238 - SG16: Unicode Direction][P1238].
Anyone wanting to follow or contribute to SG16 should become familiar with it.

We also provide input on other proposals within WG21 and WG14 when those proposals
touch on topics listed in
[P1253 - Guidelines for when a WG21 proposal should be reviewed by SG16][P1253].

The following sections list projects, Unicode papers, and ISO papers that fall
under the purview of SG16.


# Active Projects

Project     | Description/Links
----------- | -----
Boost.Text  | What a c++ standard Unicode library might look like<br/>[Code repository](https://github.com/tzlaine/text)<br/>[Documentation](https://tzlaine.github.io/text/doc/html/index.html)
ztd.text    | The premiere library for handling text in different encoding forms and reducing transcoding bugs in your C++ software<br/>[Code repository](https://github.com/soasis/text)<br/>[Documentation](https://ztdtext.readthedocs.io/en/latest)
text\_view  | A C++ Concepts based character encoding and code point enumeration library<br/>[Code repository](https://github.com/tahonermann/text_view)


# Unicode papers

Document Number | Title/Notes/Links
--------------- | -----
[L2/23-153][]   | Opposition to and Comment on L2/23–107
[L2/23-107][]   | Proper Complex Script Support in Text Terminals
[L2/21-038][]   | Clarify guidance for use of a BOM as a UTF-8 encoding signature


# ISO/IEC JTC1/SC2/WG2 (Unicode) Papers

## Active Papers

WG21 Number   | Title/Notes/Links
------------- | -----
[WG2-N5168][] | Name aliases and UTF-16 encoding scheme are inconsistent with the Unicode Standard<br/>Per [WG2-N5175][], [WG2-N5174][] contains the proposed resolution.
[WG2-N5174][] | Proposed changes concerning Character Name Aliases in ISO/IEC 10646<br/>This is the proposed resolution for [WG2-N5168][].


# ISO/IEC JTC1/SC22/WG21 (C++) Papers

## Active Papers

WG21 Number   | Title/Notes/Links
------------- | -----
[P3733][]     | More named universal character escapes
[P3717][]     | Update Annex E onto Unicode 16
[P3711][]     | Safer StringViewLike Functions for Replacing char* strings
[P3695][]     | Deprecate implicit conversions between Unicode character types
[P3688][]     | ASCII character utilities
[P3681][]     | char_traits: Stop the bleeding
[P3677][]     | Preserving LC_CTYPE at program start for UTF-8 locales
[P3672][]     | On Windows, Systems APIs, Text Encodings, and Pragmatism
[P3671][]     | Clarifying the interaction of the literal and execution encodings
[P3658][]     | Adjust identifier following new Unicode recommendations
[P3657][]     | A Grammar for Whitespace Characters
[P3655][]     | std::zstring_view
[P3566][]     | You shall not pass `char*` - Safety concerns working with unbounded null-terminated strings
[P3556][]     | Input files are source files
[P3474][]     | std::arguments
[P3412][]     | String interpolation
[P3395][]     | Formatting of std::error_code
[P3374][]     | Adding formatter for fpos<mbstate_t>
[P3364][]     | Remove Deprecated u8path overloads From C++26
[P3263][]     | Encoding annotated char
[P3258][]     | Formatting of charN_t
[P3154][]     | Deprecating signed character types in iostreams
[P3094][]     | std::basic_fixed_string
[P3070][]     | Formatting enums
[P2873][]     | Remove Deprecated Locale Category Facets For Unicode from C++26
[P2758][]     | Emitting messages at compile time
[P2749][]     | Down with ”character”
[P2729][]     | Unicode in the Library, Part 2: Normalization
[P2728][]     | Unicode in the Library, Part 1: UTF Transcoding
[P2626][]     | charN\_t incremental adoption: Casting pointers of UTF character types
[P2528][]     | C++ Identifier Security using Unicode Standard Annex 39
[P2348][]     | Whitespaces Wording Revamp
[P1953][]     | Unicode Identifiers And Reflection
[P1729][]     | Text Parsing
[P1629][]     | Standard Text Encoding
[P1628][]     | Unicode character properties
[P1030][]     | std::filesystem::path_view
[P0244][]     | Text\_view: A C++ concepts and range based character encoding and code point enumeration library

## Accepted C++26 Papers

WG21 Number   | Title/Notes/Links
------------- | -----
[P2909][]     | Fix formatting of code units as integers<br/>(Dude, where’s my char?)
[P2872][]     | Remove wstring_convert From C++26
[P2871][]     | Remove Deprecated Unicode Conversion Facets From C++26
[P2845][]     | Formatting of std::filesystem::path
[P2741][]     | user-generated static_assert messages
[P2558][]     | Add @, $, and \` to the basic character set
[P2361][]     | Unevaluated strings literals
[P2319][]     | Prevent path presentation problems
[P1885][]     | Naming Text Encodings to Demystify Them
[P1854][]     | Conversion to execution encoding should not lead to loss of meaning

## Accepted C++23 Papers

WG21 Number   | Title/Notes/Links
------------- | -----
[P2736][]     | Referencing the Unicode Standard
[P2713][]     | Escaping improvements in std::format
[P2693][]     | Formatting thread::id and stacktrace
[P2675][]     | LWG3780: The Paper (format's width estimation is too approximate and not forward compatible)
[P2653][]     | Update Annex E based on Unicode 15.0 UAX 31
[P2572][]     | std::format() fill character allowances
[P2513][]     | char8\_t Compatibility and Portability Fixes
[P2460][]     | Relax requirements on wchar\_t to match existing practices
[P2419][]     | Clarify handling of encodings in localized formatting of chrono types
[P2372][]     | Fixing locale handling in chrono formatters
[P2362][]     | Remove non-encodable wide character literals and multicharacter wide character literals
[P2316][]     | Consistent character literal encoding
[P2314][]     | Character sets and encodings
[P2295][]     | Support for UTF-8 as a portable source file encoding
[P2290][]     | Delimited escapes sequences
[P2246][]     | Character encoding of diagnostic text
[P2223][]     | Trimming whitespaces before line splicing
[P2201][]     | Mixed string literal concatenation
[P2093][]     | Formatted output
[P2071][]     | Named universal character escapes
[P2029][]     | Proposed resolution for core issues 411, 1656, and 2333; numeric and universal character escapes in character and string literals
[P1949][]     | C++ Identifier Syntax using Unicode Standard Annex 31
[P1072][]     | basic\_string::resize\_and\_overwrite

## Accepted C++20 Papers

WG21 Number   | Title/Notes/Links
------------- | -----
[P1892][]     | Extended locale-specific presentation specifiers for std::format
[P1868][]     | 🦄 width: clarifying units of width and precision in std::format
[P1423][]     | char8\_t backward compatibility remediation
[P1139][]     | Address wording issues related to ISO 10646
[P1041][]     | Make char16\_t/char32\_t string literals be UTF-16/32
[P1025][]     | Update The Reference To The Unicode Standard
[P0645][]     | Text Formatting
[P0482][]     | char8\_t: A type for UTF-8 characters and strings

## Inactive Papers

<details>
  <summary>Inactive papers list</summary>

The following papers are no longer being pursued.

WG21 Number   | Title/Notes/Links
------------- | -----
~~[P3710][]~~ | ~~zstring_view: a string_view with guaranteed null termination~~<br/>(The authors of this paper have agreed to merge their efforts with the authors of [P3655][])
~~[P2773][]~~ | ~~Considerations for Unicode algorithms~~<br/>(This is an informational paper and was reviewed by SG16 in February and March of 2023)
~~[P2498][]~~ | ~~Forward compatibility of text\_encoding with additional encoding registries~~<br/>(Dropped by the author following lack of consensus for a change in LEWG)
~~[P2491][]~~ | ~~Text encodings follow-up~~<br/>(The concerns raised in this paper were avoided by changes made in R10 of [P1885][])
~~[P2297][]~~ | ~~Wording improvements for encodings and character sets~~<br/>(The goals of this paper were mostly addressed via [P2314][])
~~[P2194][]~~ | ~~The character set of C++ source code is Unicode~~<br/>(The goals of this paper are now being pursued via [P2314][] and [P2297][])
~~[P2178][]~~ | ~~Misc lexing and string handling improvements~~<br/>(The goals of this paper are now being pursued via [P1854][], [P2223][], [P2295][], [P2297][], [P2348][], [P2316][], [P2361][], [P2362][], and [P2460][])
~~[P2020][]~~ | ~~Locales, Encodings and Unicode~~<br/>(This paper did not contain a concrete proposal and no revisions are expected; it will be used as reference material)
~~[P1880][]~~ | ~~uNstring Arguments Shall Be UTF-N Encoded~~<br/>(This proposal was withdrawn by the author upon determining that the complexity of the required wording updates would outweigh their benefits)
~~[P1879][]~~ | ~~Please Don't Rewrite My String Literals~~<br/>(This proposal was withdrawn by the author)
~~[P1859][]~~ | ~~Standard terminology for execution character set encodings~~<br/>(The goals of this proposal were accomplished via [P2314][])
~~[P1844][]~~ | ~~Enhancement of regex~~<br/>(Severe ABI concerns prevent updating `std::regex`.  We will explore deprecating and replacing it)
~~[P1097][]~~ | ~~Named character escapes~~<br/>(Superseded by P2071)
~~[P0353][]~~ | ~~Unicode Friendly Encoding Conversions for the Standard Library~~<br/>(This proposal is not being advocated at this time; more foundational concerns need to be addressed first)
~~[P0169][]~~ | ~~regex with Unicode character types~~<br/>(This proposal is not being advocated at this time; more foundational concerns need to be addressed first)
</details>


# ISO/IEC JTC1/SC22/WG14 (C) Papers

## Active Papers

WG14 Number   | Title/Notes/Links
------------- | -----
[N3366][]     | Restartable Functions for Efficient Character Conversions, r13<br/>(Previously [N2431 (R0)][N2431], [N2440 (R1)][N2440], [N2500 (R2)][N2500], [N2595 (R3)][N2595], [N2620 (R4)][N2620], [N2730 (R5)][N2730], [N2902 (R6)][N2902], [N2966 (R7)][N2966], [N2999 (R8)][N2999], [N3031 (R9)][N3031], [N3075 (R10)][N3075], [N3095 (R11)][N3095], [N3265 (R12)][N3265])
[N3145][]     | $ in Identifiers v2<br/>(Previously [N3046 (R0)][N3046])
[N3124][]     | Aligning Universal Character Names Constraints with C++
[N3095][]     | 
[N3016][]     | Unicode Length Modifiers v3
[N2948][]     | Accessing the command line arguments outside of main()
[N2932][]     | C Identifier Security using Unicode Standard Annex 39 v2<br/>(Previously [N2916 (R0)][N2916])
[N2785][]     | Delimited escapes sequences

## Accepted C23 Papers

WG14 Number   | Title/Notes/Links
------------- | -----
[N2940][]     | Removing trigraphs??!
[N2939][]     | Identifier Syntax Fixes
[N2836][]     | C Identifier Syntax using Unicode Standard Annex 31<br/>(Previously [N2777 (R0)][N2777])
[N2828][]     | Unicode Sequences More Than 21 Bits are a Constraint Violation
[N2728][]     | char16\_t & char32\_t string literals shall be UTF-16 & UTF-32 \| r0
[N2701][]     | @ and $ in source and execution character set
[N2653][]     | char8\_t: A type for UTF-8 characters and strings (Revision 1)<br/>(Previously [N2231 (R0)][N2231])
[N2594][]     | Mixed Wide String Literal Concatenation
[N2563][]     | Character encoding of diagnostic text
[N2418][]     | Adding the u8 character prefix<br/>(Previously [N2198 (R0)][N2198])

## Inactive Papers

<details>
  <summary>Inactive papers list</summary>

WG14 Number   | Title/Notes/Links
------------- | -----
~~[N3265][]~~ | ~~Restartable Functions for Efficient Character Conversions \| r12~~<br/>(Superseded by [N3366][])
~~[N3095][]~~ | ~~Restartable Functions for Efficient Character Conversions \| r11~~<br/>(Superseded by [N3265][])
~~[N3075][]~~ | ~~Restartable Functions for Efficient Character Conversions \| r10~~<br/>(Superseded by [N3095][])
~~[N3046][]~~ | ~~$ in Identifiers~~<br/>(Superseded by [N3145][])
~~[N3031][]~~ | ~~Restartable Functions for Efficient Character Conversions \| r9~~<br/>(Superseded by [N3075][])
~~[N2999][]~~ | ~~Restartable for Efficient Character Conversions \| r8~~<br/>(Superseded by [N3031][])
~~[N2983][]~~ | ~~Unicode Length Modifiers v2~~<br/>(Superseded by [N3016][])
~~[N2966][]~~ | ~~Restartable Functions for Efficient Character Conversions \| r7~~<br/>(Superseded by [N2999][])
~~[N2916][]~~ | ~~C Identifier Security using Unicode Standard Annex 39~~<br/>Superseded by [N2932][])
~~[N2902][]~~ | ~~Restartable and Non-Restartable Functions for Efficient Character Conversions \| r6~~<br/>(Superseded by [N2966][])
~~[N2875][]~~ | ~~Unicode Length Modifiers~~<br/>(Superseded by [N2983][])
~~[N2777][]~~ | ~~C Identifier Syntax using Unicode Standard Annex 31~~<br/>(Superseded by [N2836][])
~~[N2730][]~~ | ~~Restartable and Non-Restartable Functions for Efficient Character Conversions \| r5~~<br/>(Superseded by [N2902][])
~~[N2620][]~~ | ~~Restartable and Non-Restartable Functions for Efficient Character Conversions \| r4~~<br/>(Superseded by [N2730][])
~~[N2595][]~~ | ~~Restartable and Non-Restartable Functions for Efficient Character Conversions \| r4~~<br/>(Superseded by [N2500][])
~~[N2500][]~~ | ~~Restartable and Non-Restartable Functions for Efficient Character Conversions \| r2~~<br/>(Superseded by [N2595][])
~~[N2440][]~~ | ~~Restartable and Non-Restartable Functions for Efficient Character Conversions \| r1~~<br/>(Superseded by [N2500][])
~~[N2431][]~~ | ~~Restartable and Non-Restartable Functions for Efficient Character Conversions~~<br/>(Superseded by [N2440][])
~~[N2231][]~~ | ~~char8\_t: A type for UTF-8 characters and strings~~<br/>(Superseded by [N2653][])
~~[N2198][]~~ | ~~Adding the u8 character prefix~~<br/>(Superseded by [N2418][])
</details>


[L2/21-038]: https://www.unicode.org/L2/L2021/21038-bom-guidance.pdf
[L2/23-107]: https://www.unicode.org/L2/L2023/23107-terminal-suppt.pdf
[L2/23-153]: https://www.unicode.org/L2/L2023/23153-opposition.pdf
[WG2-N5168]: https://www.unicode.org/wg2/docs/n5168R1-ISO10646.pdf
[WG2-N5174]: https://www.unicode.org/wg2/docs/n5174-namesaliases.pdf
[WG2-N5175]: https://www.unicode.org/wg2/docs/n5175-cdam1.2-repertoire-update.pdf
[N3366]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n3366.htm
[N3265]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n3265.htm
[N3145]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n3145.pdf
[N3124]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n3124.pdf
[N3095]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n3095.htm
[N3075]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n3075.htm
[N3046]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n3046.pdf
[N3031]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n3031.htm
[N3016]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n3016.pdf
[N2999]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2999.htm
[N2983]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2983.pdf
[N2966]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2966.htm
[N2948]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2948.pdf
[N2940]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2940.pdf
[N2939]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2939.pdf
[N2932]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2932.htm
[N2916]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2916.htm
[N2902]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2902.htm
[N2875]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2875.pdf
[N2836]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2836.pdf
[N2828]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2828.htm
[N2785]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2785.pdf
[N2777]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2777.pdf
[N2730]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2730.htm
[N2728]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2728.htm
[N2701]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2701.htm
[N2653]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2653.htm
[N2620]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2620.htm
[N2595]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2595.pdf
[N2594]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2594.htm
[N2563]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2563.pdf
[N2500]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2500.pdf
[N2440]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2440.pdf
[N2431]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2431.pdf
[N2418]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2418.pdf
[N2231]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2231.htm
[N2198]: https://www.open-std.org/jtc1/sc22/wg14/www/docs/n2198.pdf
[P3733]: https://wg21.link/p3733
[P3717]: https://wg21.link/p3717
[P3711]: https://wg21.link/p3711
[P3710]: https://wg21.link/p3710
[P3695]: https://wg21.link/p3695
[P3688]: https://wg21.link/p3688
[P3681]: https://wg21.link/p3681
[P3677]: https://wg21.link/p3677
[P3672]: https://wg21.link/p3672
[P3671]: https://wg21.link/p3671
[P3658]: https://wg21.link/p3658
[P3657]: https://wg21.link/p3657
[P3655]: https://wg21.link/p3655
[P3566]: https://wg21.link/p3566
[P3556]: https://wg21.link/p3556
[P3474]: https://wg21.link/p3474
[P3412]: https://wg21.link/p3412
[P3395]: https://wg21.link/p3395
[P3374]: https://wg21.link/p3374
[P3364]: https://wg21.link/p3364
[P3263]: https://wg21.link/p3263
[P3258]: https://wg21.link/p3258
[P3154]: https://wg21.link/p3154
[P3094]: https://wg21.link/p3094
[P3070]: https://wg21.link/p3070
[P2909]: https://wg21.link/p2909
[P2873]: https://wg21.link/p2873
[P2872]: https://wg21.link/p2872
[P2871]: https://wg21.link/p2871
[P2845]: https://wg21.link/p2845
[P2773]: https://wg21.link/p2773
[P2758]: https://wg21.link/p2758
[P2749]: https://wg21.link/p2749
[P2741]: https://wg21.link/p2741
[P2736]: https://wg21.link/p2736
[P2729]: https://wg21.link/p2729
[P2728]: https://wg21.link/p2728
[P2713]: https://wg21.link/p2713
[P2693]: https://wg21.link/p2693
[P2675]: https://wg21.link/p2675
[P2653]: https://wg21.link/p2653
[P2626]: https://wg21.link/p2626
[P2572]: https://wg21.link/p2572
[P2558]: https://wg21.link/p2558
[P2528]: https://wg21.link/p2528
[P2513]: https://wg21.link/p2513
[P2498]: https://wg21.link/p2498
[P2491]: https://wg21.link/p2491
[P2460]: https://wg21.link/p2460
[P2419]: https://wg21.link/p2419
[P2372]: https://wg21.link/p2372
[P2362]: https://wg21.link/p2362
[P2361]: https://wg21.link/p2361
[P2348]: https://wg21.link/p2348
[P2319]: https://wg21.link/p2319
[P2316]: https://wg21.link/p2316
[P2314]: https://wg21.link/p2314
[P2297]: https://wg21.link/p2297
[P2295]: https://wg21.link/p2295
[P2290]: https://wg21.link/p2290
[P2246]: https://wg21.link/p2246
[P2223]: https://wg21.link/p2223
[P2201]: https://wg21.link/p2201
[P2194]: https://wg21.link/p2194
[P2178]: https://wg21.link/p2178
[P2071]: https://wg21.link/p2071
[P2093]: https://wg21.link/p2093
[P2029]: https://wg21.link/p2029
[P2020]: https://wg21.link/p2020
[P1953]: https://wg21.link/p1953
[P1949]: https://wg21.link/p1949
[P1892]: https://wg21.link/p1892
[P1885]: https://wg21.link/p1885
[P1880]: https://wg21.link/p1880
[P1879]: https://wg21.link/p1879
[P1868]: https://wg21.link/p1868
[P1859]: https://wg21.link/p1859
[P1854]: https://wg21.link/p1854
[P1844]: https://wg21.link/p1844
[P1729]: https://wg21.link/p1729
[P1629]: https://wg21.link/p1629
[P1628]: https://wg21.link/p1628
[P1423]: https://wg21.link/p1423
[P1253]: https://wg21.link/p1253
[P1238]: https://wg21.link/p1238
[P1139]: https://wg21.link/p1139
[P1030]: https://wg21.link/p1030
[P1097]: https://wg21.link/p1097
[P1072]: https://wg21.link/p1072
[P1041]: https://wg21.link/p1041
[P1025]: https://wg21.link/p1025
[P0645]: https://wg21.link/p0645
[P0482]: https://wg21.link/p0482
[P0244]: https://wg21.link/p0244
[P0353]: https://wg21.link/p0353
[P0169]: https://wg21.link/p0169
