# session6

# Default Values
	We can provide default values to the function arguments. Once we provide a default value to a function argument, the argument becomes optional during the function call, which means it is not mandatory to pass that argument during function call. Let’s take an example to understand this concept.

## Docstrings 
	Python documentation string or commonly known as docstring, is a string literal, and it is used in the class, module, function, or method definition. Docstrings are accessible from the doc attribute (__doc__) for any of the Python objects and also with the built-in help() function. An object's docstring is defined by including a string constant as the first statement in the object's definition.
    Docstrings are great for understanding the functionality of the larger part of the code, i.e., the general purpose of any class, module, or function, whereas the comments are used for code, statement, and expressions, which tend to be small. They are a descriptive text written by a programmer mainly for themselves to know what the line of code or expression does and also for the developer who wishes to contribute to that project. It is an essential part that documenting your code is going to serve well enough for writing clean code and well-written programs.

## Annotations
	* Function annotations, both for parameters and return values, are completely optional.

	* Function annotations are nothing more than a way of associating arbitrary Python expressions with various parts of a function at compile-time.

	* By itself, Python does not attach any particular meaning or significance to annotations

	* The PEP-3107 makes no attempt to introduce any kind of standard semantics, even for the built-in types. All this work left to the third-party libraries.

## Lambda Expression
	A lambda function is a small anonymous function.

	A lambda function can take any number of arguments, but can only have one expression.


## Functional Introspection


## Callables

## Map, Filter & Zip

## Output


## Function used
    lambda
    zip
    map
    poker_game
    create_deck
    call_lambda
    winner
    
## Results
~~~test_session6.py::test_flush_20 PASSED                                   [ 48%]
test_session6.py::test_straight_21 PASSED                                [ 51%]
test_session6.py::test_straight_22 PASSED                                [ 53%]
test_session6.py::test_straight_23 PASSED                                [ 55%]
test_session6.py::test_straight_24 PASSED                                [ 57%]
test_session6.py::test_straight_25 PASSED                                [ 59%]
test_session6.py::test_straight_26 PASSED                                [ 61%]
test_session6.py::test_three_of_a_kind_27 PASSED                         [ 63%]
test_session6.py::test_three_of_a_kind_28 PASSED                         [ 65%]
test_session6.py::test_three_of_a_kind_29 PASSED                         [ 67%]
test_session6.py::test_three_of_a_kind_30 PASSED                         [ 69%]
test_session6.py::test_two_pair_31 PASSED                                [ 71%]
test_session6.py::test_two_pair_32 PASSED                                [ 73%]
test_session6.py::test_two_pair_33 PASSED                                [ 75%]
test_session6.py::test_two_pair_34 PASSED                                [ 77%]
test_session6.py::test_one_pair_35 PASSED                                [ 79%]
test_session6.py::test_one_pair_36 PASSED                                [ 81%]
test_session6.py::test_one_pair_37 PASSED                                [ 83%]
test_session6.py::test_one_pair_38 PASSED                                [ 85%]
test_session6.py::test_one_pair_39 PASSED                                [ 87%]
test_session6.py::test_equal_hand_40 PASSED                              [ 89%]
test_session6.py::test_more_than_5_cards_41 PASSED                       [ 91%]
test_session6.py::test_less_than_3_cards_42 PASSED                       [ 93%]
test_session6.py::test_duplicate_cards_in_hands_43 PASSED                [ 95%]
test_session6.py::test_deck_creation_normal_function_44 PASSED           [ 97%]
test_session6.py::test_deck_creation_lambda_function_45 PASSED           [100%]

============================== 49 passed in 0.09s ==============================~~~
	
