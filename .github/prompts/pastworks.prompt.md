---
mode: agent
---
1. only process rest of instructions if there is index.en.md context file and it is located in content/pastworks/* . stop if otherwise.

2. create or update summary succinctly not exceeding 5 sentences based on the bullet points which appear before the bullet points. omit starting the summary with "Summary:". apply on the current file.

3. for all images listed in the front matter showcase, write a short description as a caption within 1 sentence not exceeding 12 words using the image located in src and then output into alt. apply on the current file.

4. if there were changes in instruction #2 or #3, translate content into japanese and singlish and save as index.ja.md and index.sg.md respectively, overwrite if existing.