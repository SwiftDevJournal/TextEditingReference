# TextEditingReference
A non-curated collection of tools for working with text on Apple platforms

This exists to try to encourage collaboration, reduce redundant work, and generally help those working with text make better stuff. It is a list of libraries, packages, and tools geared towards people working with text on Apple platforms. Inclusion is **strictly** non-curated. I will not apply any filters to the listings here. But, just to be extra-clear is a list of **infrastructure**, not apps.

If you know of a library or framework that should be added to the list, the easiest way to get it added is to go to [my contact page](https://swiftdevjournal.com/contact/) to send an email with a link and brief explanation of the library or framework. You can also submit a pull request.

## Views

- [CodeEditTextView](https://github.com/CodeEditApp/CodeEditTextView) (macOS, SPM)
- [CodeEditorView](https://github.com/mchakravarty/CodeEditorView) (iOS/macOS/visionOS, SPM)
- [Lexical](https://github.com/facebook/lexical-ios) (iOS, SPM)
- [MarkupEditor](https://github.com/stevengharris/MarkupEditor) (iOS/macCatalyst, SPM)
- [MarkdownEditor](https://github.com/Pallepadehat/MarkdownEditor) (macOS, SPM)
- [MetaTextKit](https://github.com/TwidereProject/MetaTextKit) (iOS, SPM)
- [NoteKit](https://github.com/tfcace/notekit) (iOS/macOS, SPM)
- [RichTextKit](https://github.com/danielsaidi/RichTextKit) (iOS/macOS/tvOS/watchOS/visionOS, SPM)
- [Runestone](https://github.com/simonbs/Runestone) (iOS/visionOS, SPM)
- [SourceView](https://github.com/ChimeHQ/SourceView) (macOS, SPM)
- [STTextView](https://github.com/krzyzanowskim/STTextView) (macOS/iOS, SPM)
- [SwiftMarkdownEngine](https://github.com/nodes-app/swift-markdown-engine) (macOS, SPM)
- [Textual](https://github.com/gonzalezreal/textual) (iOS/macOS/tvOS/watchOS/visionOS, SPM)

### Other Views

The original title of this section was views that haven't been updated in more than six months. I don't want to be constantly checking when the repo was last updated and shifting them to different sections so I changed the section title. Most of the views in this section have not been updated recently.

- [AztecEditor](https://github.com/wordpress-mobile/AztecEditor-iOS) (iOS, CocoaPods)
- [CodeEditor](https://github.com/ZeeZide/CodeEditor) (iOS/macOS/visionOS, SPM/CocoaPods)
- [CYRTextView](https://github.com/illyabusigin/CYRTextView) (iOS, CocoaPods)
- [Editor](https://github.com/mmackh/Editor) (macOS/iOS)
- [Firefly](https://github.com/ActuallyTaylor/Firefly) (iOS, SPM)
- [HighlightedTextEditor](https://github.com/kyle-n/HighlightedTextEditor)(iOS/macOS, SPM)
- [NLTextView](https://github.com/srijs/NLTextView) (macOS)
- [NTYSmartTextView](https://github.com/naoty/NTYSmartTextView) (macOS)
- [Proton](https://github.com/rajdeep/proton) (iOS/visionOS, SPM)
- [RichEditorSwiftUI](https://github.com/canopas/rich-editor-swiftui) (macOSiOS/macOS/tvOS/watchOS/visionOS, SPM/CocoaPods)
- [Sourceful](https://github.com/twostraws/Sourceful) (iOS/macOS, SPM/CocoaPods)
- [TextKit_LineNumbers](https://github.com/alldritt/TextKit_LineNumbers) (iOS)
- [TwitterTextEditor](https://github.com/twitter/TwitterTextEditor) (iOS, SPM)
- [YYText](https://github.com/ibireme/YYText) (iOS, CocoaPods)
- [ZSSRichTextEditor](https://github.com/nnhubbard/ZSSRichTextEditor) (iOS, CocoaPods)

### Archived

- [RichTextView](https://github.com/tophat/RichTextView) (iOS, SPM/Carthage/CocoaPods)
- [SavannaKit](https://github.com/louisdh/savannakit) (iOS/macOS, Carthage/CocoaPods)
- [SourceEditor](https://github.com/louisdh/source-editor) (iOS/macOS, CocoaPods)
- [SwiftDown](https://github.com/qeude/SwiftDown) (iOS/macOS, SPM)
- [SyntaxKit](https://github.com/palle-k/SyntaxKit) (iOS)

## TextKit Utilities

- [Glyph](https://github.com/ChimeHQ/Glyph): Abstractions for working with TextKit 1 and 2
- [Ligature](https://github.com/ChimeHQ/Ligature): Text selection, grouping, and manipulation in Swift
- [Rearrange](https://github.com/johnrbent/Rearrange): Swift library for working with ranges types: NSRange, IndexSet, and String.Index
- [STTextKitPlus](https://github.com/krzyzanowskim/STTextKitPlus): Collection of useful TextKit 2 helpers
- [TextViewBenchmark](https://github.com/ChimeHQ/TextViewBenchmark): A suite of performance tests for macOS text views
- [TextViewPlus](https://github.com/ChimeHQ/TextViewPlus): Make life better with NSTextView+TextKit 1/2

## Editing UI

## Editing Behavior

- [EditorConfig](https://github.com/slsrepo/EditorConfig): A Swift library for working with .editorconfig files
- [IBeam](https://github.com/ChimeHQ/IBeam): A Swift library for multi-cursor support
- [Borderline](https://github.com/chimeHQ/Borderline): Text line metrics and visualization

## Parsing

- [Citron](https://github.com/roop/citron): An LALR Parser Generator for Swift
- [Flexer](https://github.com/ChimeHQ/Flexer): Lexing library for Swift
- [Gramophone](https://github.com/ChimeHQ/Gramophone): Swift library for working with Extended Backus–Naur Form (EBNF) notation and grammars
- [ParseKit](https://github.com/itod/parsekit): Objective-C Tokenizer and Parser Generator. Supports Grammars.
- [PEGKit](https://github.com/itod/pegkit): 'Parsing Expression Grammar' toolkit for Cocoa/Objective-C
- [SwiftTreeSitter](https://github.com/tree-sitter/swift-tree-sitter): Swift API for the tree-sitter incremental parsing system
- [SwiftTreeSitter](https://github.com/viktorstrate/swift-tree-sitter): Swift bindings for the tree-sitter parsing library
- [TextMarkupKit](https://github.com/bdewey/TextMarkupKit): Pure-Swift tools for understanding and editing text files with simple markup
- [tree-sitter](https://github.com/tree-sitter/tree-sitter): An incremental parsing system for programming tools

## Text Manipulation

- [TextFormation](https://github.com/johnrbent/TextFormation): Rules system for live typing completions

## Storage

- [RelativeCollections](https://github.com/ChimeHQ/RelativeCollections): Swift collection types that support efficient storage of order-relative values
- [TextStory](https://github.com/johnrbent/TextStory): Happier, more flexible NSTextStorage

## Syntax Highlighting

- [HighlightSwift](https://github.com/appstefan/HighlightSwift): Code syntax highlighting in Swift and SwiftUI
- [HighlighterSwift](https://github.com/smittytone/HighlighterSwift): iOS & Mac Syntax Highlighter.
- [Neon](https://github.com/slsrepo/Neon): A Swift library for efficient, flexible content-based text styling
- [Splash](https://github.com/JohnSundell/Splash): A fast, lightweight and flexible Swift syntax highlighter for blogs, tools and fun!
- [SwiftHighlight](https://github.com/CreatureSurvive/SwiftHighlight): Syntax highlighting package written completely in Swift, no JavaScript.
- [ThemePark](https://github.com/slsrepo/ThemePark): A Swift library for working with syntax highlighting/IDE themes

## Search

- [FindFaster](https://github.com/Finnvoor/FindFaster)

## LSP/LSIF/DAP

- [DebugAdapterProtocol](https://github.com/johnrbent/DebugAdapterProtocol)
- [langserver-swift](https://github.com/RLovelett/langserver-swift)
- [LanguageClient](https://github.com/ChimeHQ/LanguageClient)
- [LanguageServerProtocol](https://github.com/ChimeHQ/LanguageServerProtocol)
- [SwiftDAP](https://github.com/noellee/SwiftDAP)
- [SwiftLSP](https://github.com/codeface-io/SwiftLSP)
