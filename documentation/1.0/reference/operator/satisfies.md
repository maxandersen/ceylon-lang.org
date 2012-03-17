---
layout: reference
title: `satisfies` operator
tab: documentation
unique_id: docspage
author: Tom Bentley
milestone: Milestone 1
doc_root: ../../..
---

# #{page.title}

The non-associating, binary `satisfies` operator is used to test whether its 
left-hand  operand is *satisfies* its right-hand operand.

## Usage 

    void m(Type<Void> x, Type<Void> y) {
        Boolean satisfaction = x satisfies y;
    }

## Description

### Definition

The `satisfies` operator is defined as follows:

<!-- no-check -->
    lhs.satisfiesType(rhs);

See the [language specification](#{page.doc_root}/#{site.urls.spec_relative}#equalitycomparison) 
for more details.

### Polymorphism

TODO The `satisfies` operator is [polymorphic](#{page.doc_root}/reference/operator/operator-polymorphism). 
The meaning of `satisfies` depends on the 
[`Type`](#{page.doc_root}/api/ceylon/language/metamodel/interface_Type.html) interface.

## See also

* API documentation for [`Type`](#{page.doc_root}/api/ceylon/language/metamodel/interface_Type.html)
* [`is` in the language specification](#{page.doc_root}/#{site.urls.spec_relative}#equalitycomparison)
* [operator precedence](#{page.doc_root}/#{site.urls.spec_relative}#operatorprecedence) in the 
  language specification
* [Operator polymorphism](#{page.doc_root}/tour/language-module/#operator_polymorphism) 
  in the Tour of Ceylon
