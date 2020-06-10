### VMFs explained

- basic_linear_example.vmf is the absolute bare minimum a map needs to run in terms of entities for a linear map.
- basic_staged_example is the bare minimum to get a staged map working.
- split_linear_example shows how the average linear map only really needs the `both` type for `surf_splitzone`.
- split_staged_example shows how to use both `start` and `end` split zones. This is more common to see in staged maps as there's often a landing platform and then a launch platform in a separate location.
- split_both_types_example shows how these can actually also be combined on a map, with Split ID `3` acting as the `end` of Split 2 and the `start` of Split 3.