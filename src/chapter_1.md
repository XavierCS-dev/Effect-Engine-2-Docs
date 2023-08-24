# Primitive Types

Primitive types in the Effect Engine are simple data structures that are widely used across the engine
for many different purposes. The primitive types are intended to be used by both you and the
engine itself under the hood at a low level. This is opposed to advanced types, which are designed
so you only need to interact with them at a high level. This would include the 3D camera.

Since the primtive types are so common, they are highly likely to share names with structures
from other crates. Therefore, it is encouraged that you use the types built into Effect Engine
and be careful not to import similarly named types from other crates. If you need a feature for
a particular structure or a particular data type that is not implemented in Effect Engine, please
create a feature request on the [issues](https://github.com/XavierCS-dev/Effect-Engine-2/issues) page.

Of course, feel free to use types from any other library you choose, they are just likely to be
incompatible with built in types used by the engine.