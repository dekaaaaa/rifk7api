# 👩👧👦 c\_base\_entity

| Name               | function parameter                                                                                | Return type                   | Description |
| ------------------ | ------------------------------------------------------------------------------------------------- | ----------------------------- | ----------- |
| get\_move\_type    | move\_types type                                                                                  | bool                          |             |
| get\_team          |                                                                                                   | int                           |             |
| get\_origin        |                                                                                                   | [c\_vector3d](c\_vector3d.md) |             |
| get\_mins          |                                                                                                   | [c\_vector3d](c\_vector3d.md) |             |
| get\_maxs          |                                                                                                   | [c\_vector3d](c\_vector3d.md) |             |
| get\_model\_index  |                                                                                                   | int                           |             |
| set\_model\_index  | `int` index                                                                                       | void                          |             |
| get\_studio\_model |                                                                                                   | [studiohdr\*](studiohdr.md)   |             |
| get\_matrix        |                                                                                                   | [matrix3x4](c\_matrix3x4.md)  |             |
| draw\_hitboxes     | ([`matrix3x4*`](c\_matrix3x4.md) matrix `float` time, `float` r, `float` g, `float` b, `float` a) | void                          |             |
| get\_abs\_velocity |                                                                                                   | [c\_vector3d](c\_vector3d.md) |             |
| is\_breakable      |                                                                                                   | bool                          |             |
