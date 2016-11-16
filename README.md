# Guide

ACPI dump guide
acpidump > acpidump.out
acpixtract -a acpidump.out
iasl -d dsdt.dat
vi dsdt.dsl
