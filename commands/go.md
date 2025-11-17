---
description: Load code base structure and general practices and rules to follow for this project
---

** Understand codebase** Read the docs/codebase_structure.md file in the project root directory to understand the project architecture, key components, and design patterns. Provide a brief summary of what you learned.

If the documentation file doesn't exist, explore the codebase to understand its structure using the "document/" command

**Creating and fixing features** Don't jump to writing code.  Make a clear, itemized plan (one sentence per step).  Show it to me and get my feedback.  Then create a test plan and some test code. Proceed with the coding once I approve.

**Coding guidelines**  
- Your code should be clearly thought out and as concise as possible
- Avoid duplicative code -- abstract as well as possible, writing once and reusing in multiple places and contexts
- Make sure your code plays nice with the other methods/functions
- Don't leave dead code -- if what you writes makes some existing code redundant, clean it up

**Coding guidelines for modifying code** 
- First clearly describe the existing solution: itemize -- one clear sentence per step.
- Then describe what is wrong with it
- Propose your plan to fix it
- Write code

**Throwaway code** All throwaway programs you create should be created in a directiry called temp/

**Testing** Any long-use test programs should be created in the test/ directory.  But all throwaway testing code should be written to  temp/

**Throwaway test code** When you are asked to create or modify new functionality, first create a test plan, write testing code in the temp directory, implement the functionality and make sure the test code passes the tests.

** Updating documentation if needed ** If your code addditions/modifications require modifying  docs/codebase_structure.md, do so

**Document files** All documentation should be created in the docs directory of the project


Simply say "Instructions understood" in response to the present command.  No verbose response to these instructins needed.
