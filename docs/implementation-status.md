# Sarathi — Implementation Status

## Purpose

This document distinguishes the intended design described in the academic report from the implementation achieved by the project group.

## Module Status

| Module                 | Intended purpose                                                 | Status                                              |
| ---------------------- | ---------------------------------------------------------------- | --------------------------------------------------- |
| System concept         | Define the accident-detection and emergency-response idea        | Conceptual design documented                        |
| Hardware and sensors   | Collect sensor information and identify possible accident events | Partial work; complete operation not verified       |
| GPS                    | Obtain location information for an incident                      | Intended feature; end-to-end operation not verified |
| Telegram notifications | Send accident-related notifications                              | Integration unsuccessful                            |
| Web interface          | Present accident-related information to users                    | Partial prototype; not fully functional             |
| Complete integration   | Connect hardware, notification and web modules                   | Complete end-to-end operation not achieved          |

## Personal Contribution

My main focus was the project concept, problem analysis and web-side development attempts using Core PHP and Bootstrap.

I also participated in documentation, diagrams, hardware-component arrangements and project preparation. My hardware programming involvement was limited, and I did not independently develop every module.

## Limitations

The project did not reach a fully functional end-to-end implementation. Features described in the proposed design should not be interpreted as verified working features.

## Future Work

Future work could include completing the web application, testing hardware modules individually, verifying communication between modules, and conducting integration tests.

## Note

This status summary describes the project honestly based on the implementation known to me. Any additional claims about completed modules should be added only after the corresponding implementation has been verified.
