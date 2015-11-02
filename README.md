Let's build a compiler from the ground up in Lua. Here, we will be developing our own tools from scratch along the way, which is great because Lua doesn't come with much in terms of its standard library so we get to do a lot platforming work as well :)

I will be focusing heavier on the parsing aspect of this compiler as that is the low-hanging fruit aspect of compiler construction that I haven't had a chance to explore deeply yet.

Status Report:
1. Regular expressions: completed!
2. Lexer: backend completed, pending Parser to self-host the frontend as well.

TODO:
3. LL(1) Parser, which will use the graph reduction to efficiently compute the fixed point.
4. LR(0-1) Parser, which will also use a similar mechanism
5. Self-hosting the Lexer.
6. Self-hosting the Parser.
7. Type-induction.
8. Type inferencing.
9. Interpreter.