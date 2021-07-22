# Practical Work No. 2
## Flex & Yacc

### Goals
This practical work had as main objectives:
* to increase the experience of using the Linux environment, the C imperative language (for encoding data structures and respective manipulation algorithms), and some programming support tools;
* review and increase the ability to write context-independent grammars (GIC) that satisfy the LR() condition to create Domain Specific Languages (DSL);
* develop language processors according to the syntax-directed translation method, supported by a translator grammar (GT);
* use compiler generators like flex/yacc pair.

## Conversor toml2json
Tasks performed:
1. Specification of the concrete grammar of the input language.
2. Development of a lexical and syntactic recognizer for this language using a pair of generator tools
Flex/Yacc.
3. Construction of a code generator that produces the requested response. This code generator was built by associating
semantic actions of translation to grammar productions, resorting once again to the Yacc generator.