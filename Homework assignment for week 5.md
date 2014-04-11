GuoZilong(13126077)

My understanding of formal methods in general and model checking in particular.

formal methods in general

When formal methods are used for software development, formal specifications are used upstream for requirement analysis and product specifications, and formal verifications or analyses are used downstream to verify the design and code before additional verification and validation (V&V) activities are carried out. Therefore, the use of formal methods can be summarized in the following two-step process:

Constructing formal specifications: The expected behavior and other properties of the software artifacts are represented in formal models. These models of program code, design, and expected behavior are typically product-dependent, which can be specifically constructed for formal verification and analysis purposes. However, to reduce cost as well as to benefit from formal development methods, these models can be the same as the formal specifications or adapted by formalizing informal specifications for the product.
Performing formal verijications: Formal analysis techniques are applied on the product components, typically product code or formal designs, to verify their correctness with respect to their formal specifications, or to check for certain properties. These techniques are typically organized as a product-independent framework of rules that serve as the basis of formal inferences or analyses. The most common type is a set of axioms used in correctness verification.
model checking in particular

The model checker is a software that runs an algorithm to check the validity of the proposition. If it is checked to be true, a proof is said to be produced. Otherwise, a counterexample is given, much like a failed test case that can be analyzed further for defect fixing.