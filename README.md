# Digital Multi-Access Key

Species identification key which enables the user to freely choose the characteristics of a species that are convenient to evaluate for recognition.

## Prolog

Prolog is a logic programming language (PROgramming in LOgic) associated with artificial intelligence and computational logistics. It is significantly different from conventional procedural programming. Essentially, logical relationships are asserted and Prolog is used to determine whether certain statements are true, and if true, what variable bindings make them true.

Prolog is an ideal language for this project because of the fact that species traits can be logically linked by implications. This enables a digital multi-access key to have more flexibility in drawing conclusions from the information given by the user.

## Installing Amzi! Prolog + Logic Server + IDE

[Click here to travel to the installation page.](https://amzi.com/AmziOpenSource/downloads.php)

Find the downloaded file and complete the navigations below.

amzi_apls_(etc) -> apls -> bin -> wideA

This should open the Amzi! Development Environment.

## Coding in Prolog

Open a file and name it hello_world.pro. Then create the following rule:

```prolog
hello_world :-
  write('Hello, World!'), nl.
```
A rule is a predicate expression that uses logical implication (:-) to describe a relationship among facts. In this case, the code above can be interpreted as: hello/_ if 'Hello, World!' is printed.

To 'consult' the source code, the Prolog Listener will be used. Save the file and start the Listener. The following prompt should be shown:

```prolog
?-
```

Consulting the file will load the file to the listener. This can be done directly from the listener:

```prolog
?- consult(hello_world).
yes
```

Each command will return either yes or no: yes if the 
