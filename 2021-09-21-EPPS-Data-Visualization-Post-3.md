# What is literate programming (Knuth 1984)?
Before we get into the content in Kunth (1984), let me introduce the two program languages used in developing WEB language. The resources come from wikipedia.

TeX, stylized within the system as TEX, is a typesetting system which was designed and written by the author and first released in 1978. TeX is a popular means 
of typesetting complex mathematical formulae; it has been noted as one of the most sophisticated digital typographical systems. TeX was designed with two main 
goals in mind: to allow anybody to produce high-quality books with minimal effort, and to provide a system that would give exactly the same results on all 
computers, at any point in time (together with the Metafont language for font description and the Computer Modern family of typefaces).

Pascal enabled defining complex datatypes and building dynamic and recursive data structures such as lists, trees, and graphs. Pascal has strong typing on all 
objects, which means that one type of data cannot be converted to or interpreted as another without explicit conversions. Unlike C (and most languages in the 
C-family), Pascal allows nested procedure definitions to any level of depth, and also allows most kinds of definitions and declarations inside subroutines 
(procedures and functions). A program is thus syntactically similar to a single procedure or function. This is similar to the block structure of ALGOL 60, 
but restricted from arbitrary block statements to just procedures and functions. It was widely used as a teaching language in university-level programming 
courses in the 1980s, and also used in production settings for writing commercial software during the same period. It was displaced by the C programming 
language during the late 1980s and early 1990s as UNIX-based systems became popular, and especially with the release of C++.

In his article, Knuth points out that instead of imaging that our main task is to instruct a computer what to do, we could try to concentrate on explaining 
to human beings what we want a computer to do, which is different from what structured programming highlights. He develops the concept of literate programming, 
a way of producing compliable source code and cross-linked documentation typeset in TeX from the same original file. The language used is called WEB and produces 
programs in DEC PDP-10 Pascal. His prototype WEB system uses TEX as the document formatting language and PASCAL as the programming language.

However, the WEB language has some requirements for users, including being good enough at computer science, being comfortable dealing with several program languages
simultaneously, etc. But his idea of literate programming has spreaded rapidly and has an effect on the evolution of programming broadly.
