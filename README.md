# TMUX_USAGE_CONFIG

![](ZZZ/ZZZ.jpg) 

## PREFIX FOR TMUX
* Default `<PREFIX>` is `<CTRL-b>`
* Custom `<PREFIX>` is `<CTRL-SPACE>`

## PLUGIN and REFRESH
| KEYMAPPING | EFFECT |
| ---------- | ------ |
| `<PREFIX> I` | Update and install plugins |
| `<PREFIX> r` | Reload config |

## TERMINAL USAGE
| COMMAND | EFFECT |
| ------- | ------ |
| `tmux` | Start a fresh session |
| `tmux ls` | See all running sessions |
| `tmux new -s SESSION_NAME` | Start a new session with a name |
| `tmux a -t SESSION_NAME` | Attach to a tmux session |
| `tmux kill-session -t SESSION_NAME` | Kill session |

## SESSION
| COMMAND | EFFECT |
| ------- | ------ |
| `<PREFIX> D` | Detach from a session |

## PANES
| COMMAND | EFFECT |
| ------- | ------ |
| `<PREFIX> v` | Vertically splited panes |
| `<PREFIX> h` | Horozontally splitted panes |
| `M-ARROW_KEYS` | Move to pane |
| `<PREFIX>-q window_index` | Move between panes |
| `<PREFIX>-arrow_keys` | Change size of panes |

## PRESELECTED LAYOUTS
| COMMAND | EFFECT |
| ------- | ------ |
| `<PREFIX> ALT-NUMBER` | Number ranges from 1 to 5 |

## YANKING
| COMMAND | EFFECT |
| ------- | ------ |
| `<PREFIX> [` | Enter copy mode |
| `<SPACE>` | Start copying |
| `<ENTER>` | When finished copying |
| `<PREFIX> ]` | Paste |

## WINDOW MANAGEMENT
| KEYMAPPING | EFFECT |
| ---------- | ------ |
| `<PREFIX> n` | Create new window |
| `S-LEFT_KEY` | Goto previous window |
| `S-RIGHT_KEY` | Goto next window |
| `<PREFIX> w` | Goto selected window |
| `<PREFIX> ,` | Rename window |
| `<PREFIX> x` | Kill the present pane |
| `<PREFIX> &` | Kill the present window |

## ZOOM
| KEYMAPPING | EFFECT |
| ---------- | ------ |
| `<PREFIX> z` | Toggle pane zoom |

## PANE AND WINDOW NAVIGATOR
| KEYMAPPING | EFFECT |
| ---------- | ------ |
| `<PREFIX> s` | Navigate bet window and panes together |
| `<PREFIX> w` | Session and window preview |

## NAVIGATE BETWEEN sessions
| KEYMAPPING | EFFECT |
| ---------- | ------ |
| `<PREFIX> (` | Goto previous session |
| `<PREFIX> )` | Goto next session |

## OPEN COMMAND MODE
| KEYMAPPING | EFFECT |
| ---------- | ------ |
| `<PREFIX> :` | To enter command mode |
