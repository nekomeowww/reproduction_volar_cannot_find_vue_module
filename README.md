# Reproduction Volar `cannot find module` issue

This reproduction repo demonstrates the `cannot find module <file_name>.vue or its corresponding type declaration` error when component lives in a `.` prefixed directory.

Navigate to `.dot/C1.vue` to see the error. This issue occurs in both the import statement in `.vue` component and `.ts` modules.
