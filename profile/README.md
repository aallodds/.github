# AAO (Against All Odds)
- Established: October 5th, 2025.
- Founders: Grant Abernathy & Kendalynn Kohler.
- Mission: Provide programmers and game designers and anyone in the programming / art industry with tools and a place to create their amazing ideas. Giving people a place to let their ideas shine to the fullest.
- Logo is temporary.

# Programming Guidelines
This here will tell you the guidelines of programming and things like that :)

## General Guidelines and Codestyle
- Use spaces for indentation, never tabs. Many editors will incorrectly show tab indentation and it's just a mess.
- Use space indentation size four or two.
- Always use ``LF`` for line endings, except if it's ``.bat``, ``.cmd`` files since those **require** ``CRLF`` line endings to execute properly.
- Always move braces to a new line. Brace wars are foul, but here, we have always moved braces to a new line.
- Always follow ``PascalCase``, this is the primary naming convention, and you shouldn't shy away from it at all, whatsoever.
- For C++ source files, use ``cc/hh``.
- For C source files, use ``c/h``.
- Always seperate IDE project files from code directories, looking at you... Visual Studio.

## C++/C Guidelines and Codestyle
- ``C++ 20`` should be the **minimum** target standard for new ``C++`` projects.
- ``C 18`` should be the **minimum** target standard for new ``C`` projects.

- Use ``b`` for booleans. ``bIsSomething``
- Use ``str`` for strings. ``strWindowTitle``
- Use ``i`` for integers. ``iAmountOfSomething``
- Use ``f`` for floats. ``fFloat``
- Use ``E`` for enums. ``ECompiler``
- Use ``S`` for structs. ``SModelInfo``
- Use ``I`` for interface classes. ``IAllocator``
- Use ``C`` for classes. ``CPoolAllocator``