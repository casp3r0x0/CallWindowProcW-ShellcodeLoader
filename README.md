# About 

this is simple shellcode loader that utilize not well known WinAPI function which is `CallWindowProcW` to execute the shellcode without creating a new thread. 

1. It runs arbitrary code.

2. It accepts any function pointer and executes it without checks.

3. No new thread is required—execution occurs on the existing GUI thread, avoiding EDRs that monitor thread creation.

4. It appears legitimate for GUI applications, as calling window procedures and processing messages is normal behavior, helping it blend in.


<img width="1067" height="712" alt="Screenshot 2025-09-01 042556" src="https://github.com/user-attachments/assets/e52c1b05-a112-42fe-80d2-ff0bbdc7cd54" />
