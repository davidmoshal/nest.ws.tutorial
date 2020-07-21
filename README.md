notes:
- broken: run the server with the start:debug script
  - problem is that any code edits lose the breakpoints.
  - curiously, the nodejs devtools chrome panel is great, handles codes edits, etc.
- this is much better: (`working`)
    - "start:dev:dm": "tsc-watch -p tsconfig.build.json --onSuccess \"node dist/main.js\"",
    `  ``"tsc-watch -p tsconfig.build.json --onSuccess "node dist/main.js" `  
 
