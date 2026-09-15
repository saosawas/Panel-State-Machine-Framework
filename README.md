In LabVIEW 2020 and later (including LabVIEW 2021), National Instruments introduced native Interfaces.
Interfaces allow you to implement a form of multiple inheritance, where a class can inherit from one parent class but implement multiple interfaces.
Using an interface to handle dynamic subpanel loading is an excellent architecture. It decouples your main user interface (UI) from the specific implementation of the subpanels.
