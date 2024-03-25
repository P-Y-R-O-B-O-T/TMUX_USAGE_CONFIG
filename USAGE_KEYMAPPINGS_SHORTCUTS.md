# UASGE AND KEYMAPPINGS FOR TMUX_3.2a

## TERMINOLOGY
* `sessions`
* `windows`
* `panes`

## TERMINAL USAGE
* `tmux` Start a fresh session
* `tmux ls` See all running sessions
* `tmux new -s session_name` Start a new session with a name
* `tmux a -t session_name` Attach to a tmux session
* `tmux kill-session -t session_name`

## PREFIX FOR TMUX
* Default `<prefix>` is `<ctrl-b>`
* Custom `<prefix>` is `<C-space>`

## DETACH FROM A SESSION
* `<prefix> D` Detach from a session

## PANES
* `<prefix> v` Vertically splited panes
* `<prefix> h` Horozontally splitted panes
* `M-up_key` Move to upper pane
* `M-down_key` Move to upper pane
* `M-right_key` Move to right pane
* `M-left_key` Move to left pane
* `<prefix>-q window_index` Move between panes
* `<prefix>-arrow_keys` Change size of panes

## PRESELECTED LAYOUTS
* `<prefix> alt-number` Number ranges from 1 to 5

## YANKING
* `<prefix> [` Enter copy mode
* `<space>` Start copying
* `<Enter>` When finished copying
* `<prefix> ]` Paste

## WINDOW MANAGEMENT
* `<prefix> n` Create new window
* `S-left_key` Goto previous window
* `S-right_key` Goto next window
* `<prefix> w` Goto selected window
* `<prefix> ,` Rename window
* `<prefix> x` Kill the present pane
* `<prefix> &` Kill the present window

## ZOOM
* `<prefix> z` Toggle pane zoom

## PANE AND WINDOW NAVIGATOR
* `<prefix> s` Navigate bet window and panes together
* `<prefix> w` Session and window preview

## NAVIGATE BETWEEN sessions
* `<prefix> (` Goto previous session
* `<prefix> )` Goto next session


## OPEN COMMAND MODE
* `<prefix> :` To enter command mode
