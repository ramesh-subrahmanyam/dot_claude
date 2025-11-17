# Code Refactor Command

Systematically clean up Python codebases by identifying issues and creating safe refactoring plans.

## Process

When invoked, this command will:

1. **Analyze** - Iterate through all Python files in the project
2. **Identify Issues** - Check each file for:
   - Needlessly verbose code
   - Dead code
   - Duplicated functions
   - overlap and duplication across files
3. **Refactir** Abstract duplicated code and/or functionality.

4. **Plan** - Write a comprehensive plan to clean up the codebase. If there are no important changes to make, say so and stop.

5. **Test First** - Create a test script that thoroughly checks that any changes will be correct

6. **Execute Safely** - Proceed file by file:
   - Describe proposed changes
   - Ask for permission before making changes
   - Make changes only if permitted

7. Update documentation by rerunning the "/document" command.

## Safety First

This command prioritizes safety by:
- Creating test scripts before making any changes
- Asking for permission before modifying each file
- Working incrementally, one file at a time

Use this command when you need to refactor or clean up Python code while maintaining correctness and safety.
