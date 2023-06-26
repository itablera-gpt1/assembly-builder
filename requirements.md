Create a page with three drop down menus: Adaptor, Tools, Inserts

These three menus should be linked to one another according to following tables:


|        | Insert 1 | Insert 2 | Insert 3 |
|--------|----------|----------|----------|
| Tool 1 |    x     |          |          |
| Tool 2 |    x     |    x     |          |
| Tool 3 |          |          |    x     |

|          | Tool 1 | Tool 2 | Tool 3 |
|----------|--------|--------|--------|
| Adaptor 1|        |        |    x   |
| Adaptor 2|   x    |   x    |        |
| Adaptor 3|   x    |        |   x    |

If the user select "Tool 1" in the tool drop down, then only "Adaptor 2" and "Adaptor 3" should be displayed in Adaptor dropdown and only "Insert 1" should be available in the Insert drop down menu
