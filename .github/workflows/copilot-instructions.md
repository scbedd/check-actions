## Pull Request Guidelines

- Create the auto-generated PR body as normal, but `copilot` should add an additional section after all of its regular PR body content. That should look something like:
  ```
  ## Invoking Livetests

  To run mcp livetests after verify the contents of this PR are not nefarious, a user with `write` access needs to leave a comment on this PR with the text `/azp run mcp - pullrequest - live`. This will trigger the necessary livetest workflows to complete required validation.
  ```