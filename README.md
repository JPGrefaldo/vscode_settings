{
	"editor.detectIndentation": true,
	"explorer.openEditors.visible": 0,
    "editor.fontFamily": "Operator Mono Lig",
    "editor.fontLigatures": true,
    "editor.parameterHints.enabled": false,
    "editor.minimap.enabled": false,
    "workbench.statusBar.visible": true,
    "editor.lineHeight": 25,
    "editor.selectionHighlight": false,
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.quickSuggestions": true,
    "html.suggest.html5": true,
    "editor.tabCompletion": "on",
    "debug.allowBreakpointsEverywhere": true,
    "vetur.validation.template": false,
    // "eslint.validate": [{
    //         "language": "vue",
    //         // "autoFix": true,
    //         "skipTemplates": false
    //     },
    //     {
    //         "language": "html",
    //         //   "autoFix": true
    //     },
    //     {
    //         "language": "javascript",
    //         //   "autoFix": true
    //     }
    // ],
    // "eslint.autoFixOnSave": true,
    // "editor.formatOnSave": true,
    // "files.associations": {
    //     // ".blade.php": "html",
    //     ".tpl": "html"
    // },
    "vetur.completion.useScaffoldSnippets": false,
    "vim.experimentalOptimizations": true,
    "vim.easymotion": true,
    "vim.sneak": true,
    "vim.incsearch": true,
    "vim.useSystemClipboard": true,
    "vim.useCtrlKeys": true,
    "vim.hlsearch": true,
    "git.enableCommitSigning": true,
    "vim.insertModeKeyBindings": [{
        "before": [
            "j",
            "j"
        ],
        "after": [
            "<Esc>"
        ]
    }],
    "vim.normalModeKeyBindingsNonRecursive": [{
            "before": [
                "<leader>",
                "d"
            ],
            "after": [
                "d",
                "d"
            ]
        },
        {
            "before": [
                "<C-n>"
            ],
            "after": [],
            "commands": [{
                "command": ":nohl"
            }]
        },
        {
            "before": [
                "<leader>",
                "o"
            ],
            "after": [
                "o",
                "<Esc>",
                "k"
            ]
        },
        {
            "before": [
                "g",
                "C-a"
            ],
            "commands": [
                "progressive.incrementBy1"
            ]
        }
    ],
    "vim.leader": "<space>",
    "vim.handleKeys": {
        "<C-a>": false,
        "<C-f>": false,
        "<C-c>": false
    },
    "emmet.includeLanguages": {
        "php": "html"
    },
    "workbench.colorCustomizations": {
        // "editorGutter.background": "#24292A",
        // "editor.background" : "#24292A"
    },
    "workbench.editor.showTabs": true,
    "editor.acceptSuggestionOnEnter": "smart",
    "editor.snippetSuggestions": "top",
    "editor.suggestOnTriggerCharacters": false,
    "editor.suggestSelection": "first",
    // "php-cs-fixer.onsave": true,
    "php-cs-fixer.executablePath": "${extensionPath}/php-cs-fixer.phar",
    "php-cs-fixer.lastDownload": 1627552673014,
    "php-cs-fixer.config": "/home/jpgrefaldo/.vscode/.php_cs",
    "gitlens.advanced.messages": {
        "suppressShowKeyBindingsNotice": true
    },
    "gitlens.codeLens.enabled": false,
    "gitlens.hovers.currentLine.over": "line",
    "diffEditor.ignoreTrimWhitespace": false,
    "window.titleBarStyle": "native",
    "gitlens.views.fileHistory.enabled": true,
    "gitlens.views.lineHistory.enabled": false,
    "editor.smoothScrolling": true,
    "workbench.sideBar.location": "left",
    // The direct answer to this question is (from this github page):
    // Add this to settings.json (ctrl + , or cmd + ,)
    "editor.tokenColorCustomizations": {
        "textMateRules": [{
                "scope": [
                    //following will be in italic (=FlottFlott)
                    "comment",
                    "entity.name.type.class", //class names
                    "keyword", //import, export, return…
                    "constant", //String, Number, Boolean…, this, super
                    "storage.modifier", //static keyword
                    "storage.type.class.js" //class keyword
                ],
                "settings": {
                    "fontStyle": "italic"
                }
            },
            {
                "scope": [
                    //following will be excluded from italics (VSCode has some defaults for italics)
                    "invalid",
                    "keyword.operator",
                    "constant.numeric.css",
                    "keyword.other.unit.px.css",
                    "constant.numeric.decimal.js",
                    "constant.numeric.json"
                ],
                "settings": {
                    "fontStyle": ""
                }
            }
        ]
    },
    "editor.autoClosingQuotes": "always",
    "intelephense.files.maxSize": 1e+34,
    "editor.insertSpaces": false,
    "editor.maxTokenizationLineLength": 200000,
    "typescript.disableAutomaticTypeAcquisition": true,
    "[php]": {
        "editor.defaultFormatter": "junstyle.php-cs-fixer"
    },
    "terminal.external.osxExec": "iTerm.app",
    "gitlens.views.compare.files.layout": "list",
    "gitlens.views.repositories.files.layout": "list",
    "files.maxMemoryForLargeFilesMB": 114096,
    "files.watcherExclude": {
        "**/production.js": true,
        "**/production.min.js": true,
        "**/vendor":true,
        "**/public/js": true
    },
	"workbench.fontAliasing": "antialiased",
	"workbench.activityBar.visible": false,
	"explorer.confirmDelete": false,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "colorize.include": [
        "colorize.languages"
    ],
    "colorize.languages": [
        "javascript",
        // ...
    ],
    "scss.lint.argumentsInColorFunction": "ignore",
    "python.defaultInterpreterPath": "/usr/local/opt/python@3.8/bin/python3.8",
    "python.linting.enabled": false,
    "githubPullRequests.fileListLayout": "tree",
    "dart.previewLsp": true,
    "dart.debugExternalLibraries": false,
    "dart.debugSdkLibraries": false,
    "C_Cpp.default.cppStandard": "c++11",
    "files.exclude": {
        "**/public/js/**": true,
        "**/public/js/app.js": true,
        "**/XCBuildData": true,
        "/Users/admin/Sites/assessor/public/js/app.js": true,
        "public/js/**": true,
        "**/.classpath": true,
        "**/.project": true,
        "**/.settings": true,
        "**/.factorypath": true
    },
    "vim.foldfix": true,
    "terminal.explorerKind": "external",
    "terminal.integrated.tabs.enabled": false,
    "terminal.integrated.defaultProfile.osx": "zsh",
    "terminal.integrated.allowChords": false,
    "svg.preview.mode": "svg",
    "editor.cursorStyle": "line",
    "editor.lineNumbers": "on",
    "editor.wordSeparators": "/\\()\"':,.;<>~!@#$%^&*|+=[]{}`?-",
    "editor.wordWrap": "off",
    "editor.fontSize": 13,
    "workbench.editorAssociations": {
        "*.ipynb": "jupyter-notebook"
    },
    "notebook.cellToolbarLocation": {
        "default": "right",
        "jupyter-notebook": "left"
    }
}
