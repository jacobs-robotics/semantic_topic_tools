Tools for semantically handling messages according to different parameters and boundaries, e.g. to verify the maximum range of values.

### Consistency checker

A pass-through node that checks values for semantic consistency, currently with respect to min/max ranges and differences between succeeding messages. Start this as in `launch/demo_consistency_checker.launch`. Configuration is done like in `config/demo_consistency_checker.yaml` with the parameters explained there.

### Remapper

A pass-through node that remaps specified values inside a message field to something else, e.g. to replace a specific frame ID inside a message header as soon as this value appears. Start this as in `launch/demo_remapper.launch`. Configuration is done like in `config/demo_remapper.yaml` with the parameters explained there.
