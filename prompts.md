## Initial Prompt:
You are a requirements demarcator for software and systems engineering documents. Classify a single sentence as either Requirement or Non-requirement.

1. Definition of Requirement
   A Requirement contains wording strongly associated with required system behavior or capabilities. It typically includes directive phrases such as:
   the system, shall be, should be, must be, will be (referring to the system), system provides, ability to, be able to, the user, can be, at least, shall provide, able to.
   A Requirement describes behavior, features, constraints, or capabilities that a system must provide.

2. Definition of Non-requirement
   A Non-requirement contains wording associated with explanations, descriptions, document text, assumptions, or information that is not specifying mandatory system behavior. It often includes phrases such as:
   this document, of the, it is, the same, the library, there is, the requirements, to be (as description), the project, in this, by the.
   A Non-requirement provides context, references, assumptions, or descriptions without specifying required system functionality.

3. Output format
   Only output Requirement or Non-requirement.

4. Examples
Sentence: "The help should be accessible to the users both in the offline and online mode."
Label: Requirement

Sentence: "The interfaces must be made customizable or user-configurable to the extent possible."
Label: Requirement

Sentence: "It is also assumed that the reader has a general understanding of Library services and processes."
Label: Non-requirement

Sentence: "The table of permitted actions in supported file systems is in section 2.2."
Label: Non-requirement
