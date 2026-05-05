---
title: "Managing ARB translation files in Flutter"
url: "https://simplelocalize.io/blog/posts/manage-arb-translation-files-flutter"
date: "Wed, 21 Jan 2026 00:00:00 GMT"
author: ""
feed_url: "https://simplelocalize.io/feed.xml"
---
ARB (Application Resource Bundle) files are the standard way to handle localization in Flutter applications. They are simple JSON files, but with a few important conventions that make them powerful for translations: metadata, descriptions, placeholders, plurals, and gender rules.

In this article, we will take a practical look at ARB files, how they work in Flutter, common challenges teams face when managing them, and how SimpleLocalize helps you keep translations under control as your app grows.

If you have worked with other formats like XLIFF, CSV, PO/POT, or YAML, you will notice that ARB has its own quirks. Understanding them early will save you time later.

What is an ARB file?

ARB stands for Application Resource Bundle. Technically, it's a JSON file with a naming convention and a few reserved keys used by Flutter's localization tooling.

A typical ARB file looks like this:

Each file represents a single locale. For example:

app_en.arb for English

app_de.arb for German

app_es.arb for Spanish

Flutter uses these files together with flutter_localizations and intl to generate strongly typed localization code.

Learn more about setting up Flutter localization in the official Flutter docs on internationalization.

ARB metadata and descriptions

One important difference between ARB and plain JSON is metadata entries. Any key that starts with @ is treated as metadata for the corresponding message.

Example:

In this example, the @welcomeUser key provides additional context for translators, like descriptions and placeholder details. Why this matters:

Translators see context, not just raw strings

Placeholders are clearly defined, reducing errors

Flutter can generate safer localization code

When metadata is missing, translations often become ambiguous. A short description can prevent many mistakes.

Currently SimpleLocalize supports descriptions metadata. Placeholder details are not yet supported but are planned for future releases. Learn more in our ARB integration documentation.

Handling placeholders in ARB files

Placeholders allow you to inject dynamic values into translations. In ARB files, placeholders are written using curly braces:

In the metadata section, you define the placeholder details:

Tips for placeholders:

Use clear, descriptive names (userName instead of name)

Keep placeholder usage consistent across languages

Avoid embedding formatting logic directly in strings

When translators see well-defined placeholders, they can create accurate translations without guessing.

Plurals and ICU message format

ARB files use ICU MessageFormat, which allows proper pluralization and complex language rules.

Example of pluralization:

This approach is much better than string concatenation and works correctly for languages with complex plural rules.

When managing plurals:

Always use ICU syntax instead of manual logic

Test plural forms in multiple languages

Keep messages readable — long ICU strings benefit from descriptions

SimpleLocalize fully supports ICU message format in ARB files, making it easy to manage plurals and complex translations.

Common challenges with ARB files

ARB files are simple at first, but real projects grow quickly. Common issues include:

Missing or outdated translations: As new keys are added, older ARB files may fall behind. Without visibility, it's easy to ship incomplete translations.

Lack of context for translators: Without descriptions and screenshots, translators guess, and guessing leads to errors.

Broken placeholders: Renaming or removing placeholders without updating translations can cause runtime errors.

Large files and merge conflicts: ARB files often live in Git. When many people edit the same file, conflicts become frequent.

Inconsistent formatting: Manual edits can lead to formatting issues that break parsing.

These challenges can make ARB file management painful without the right tools and processes.

Managing ARB files with SimpleLocalize

SimpleLocalize supports ARB files natively, making it easy to upload, manage, and download translations. Integrate it into your Flutter workflow with just a few steps.

Importing ARB files

You can upload ARB files directly to SimpleLocalize. The system:

Reads message keys and values

Extracts metadata and descriptions

Detects and validates placeholders automatically

This makes it easy to start from existing Flutter projects.

Importing ARB files in SimpleLocalize

Editing translations safely

In SimpleLocalize:

Placeholders are protected from accidental removal

Plural rules are clearly visible

Descriptions help translators understand usage

Validation checks ensure consistency across languages

This reduces the risk of broken builds caused by incorrect translations.

Add more languages, run auto-translation and quality checks, update review statuses, add more context with screenshots — all from a user-friendly interface.

Editing ARB translations in SimpleLocalize

Collaboration and workflow

Instead of editing ARB files manually:

Developers focus on source language updates

Translators work in a dedicated UI

Reviewers can approve changes before export

This separation keeps ARB files clean and predictable.

Exporting back to Flutter

Once translations are ready, you can export them back as ARB files:

One file per locale

No manual formatting required

Placeholders intact

The exported files can be committed directly to your repository or integrated into your CI/CD pipeline.

Exporting ARB files from SimpleLocalize

Learn more about SimpleLocalize's CLI tools and REST API for automating ARB file management.

Best practices for ARB localization

Here are a few tips that work well in real projects:

Use descriptive keys: Instead of generic keys like msg1, use welcomeUser or errorNetwork

Keep keys stable: changing keys breaks existing translations

Write descriptions early: context is cheaper than fixes

Use one source language: usually English

Validate placeholders during code reviews

Avoid duplicate strings with different meanings

Regularly sync ARB files with your localization platform

Small habits make a big difference over time. By following these practices, you can keep your ARB files manageable and your translations accurate.

Conclusion

ARB files are easy to start with, but managing them at scale requires structure and good tooling. With clear metadata, consistent placeholders, and a solid workflow, Flutter localization becomes predictable instead of painful. Using a platform like SimpleLocalize takes much of the manual work out of managing ARB files, letting your team focus on building great apps that speak multiple languages.

Get started with SimpleLocalize today and see how it can help you manage ARB translation files in Flutter with ease!
