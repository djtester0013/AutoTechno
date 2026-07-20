---
name: "Fix failing CI: Gradle configuration error in :mobile"
about: "Pin Kotlin to 1.9.22, enable kotlin-parcelize, update Parcelize import"
---

This pull request pins the Kotlin Gradle plugin to 1.9.22, enables the kotlin-parcelize plugin in the mobile module, and updates the Parcelize import to kotlinx.parcelize.Parcelize.

These changes resolve a Gradle configuration error related to org.jetbrains.kotlin.gradle.plugin.statistics.BuildFlowService observed during the CodeQL workflow.
