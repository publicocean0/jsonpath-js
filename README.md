# jsonpath-js
<pre>
jsonPath(obj, expr [, args])
</pre>
parameters:

-obj (object|array):Object representing the JSON structure.
-expr (string):JSONPath expression string.
-args (object|undefined):Object controlling path evaluation and output. Currently only one member is supported.
args.resultType ("VALUE"|"PATH"):
causes the result to be either matching values (default) or normalized path expressions.
-return value:(array|false):

Array holding either values or normalized path expressions matching the input path expression, which can be used for lazy evaluation. false in case of no match
