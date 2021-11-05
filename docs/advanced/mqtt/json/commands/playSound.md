# PlaySound command

## `playSound`

Command to play a sound or voice report

### Request

{%
   include-markdown "../../../../../include/advanced/mqtt/json/commands/request.md"
%}

- Name: `playSound`
- Arguments:
  - `sid`: The ID of the sound

!!! info "Available sound IDs"

    For a list of available sound IDs see [here](https://github.com/mrbungle64/ecovacs-deebot.js/wiki/playSound#available-sound-ids)

{%
    include-markdown "../../../../../include/advanced/mqtt/json/commands/execute/response.md"
    heading-offset=2
%}