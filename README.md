{
	"editor.detectIndentation": true,
	"explorer.openEditors.visible": 0,
	"editor.fontSize": 11,
	"editor.fontLigatures": true,
	"editor.parameterHints.enabled": true,
	"editor.minimap.enabled": false,
	"workbench.statusBar.visible": true,
	"editor.lineHeight": 28,
	"editor.selectionHighlight": false,
	"editor.multiCursorModifier": "ctrlCmd",
	"editor.quickSuggestions": {
		"comments": "on",
		"strings": "on",
		"other": "on"
	},
	"html.suggest.html5": true,
	"editor.tabCompletion": "on",
	"debug.allowBreakpointsEverywhere": true,
	"vetur.validation.template": false,
	"typescript.inlayHints.parameterNames.enabled": "all",

	"eslint.validate": ["javascript", "javascriptreact", "typescript", "typescriptreact", "vue", "html", "php"],
	"editor.codeActionsOnSave": {
		"source.fixAll.eslint": "explicit"
	},
	"files.associations": {
		".tpl": "html",
		"*.py": "python"
	},
	"vim.easymotion": true,
	"vim.sneak": true,
	"vim.incsearch": true,
	"vim.useSystemClipboard": true,
	"vim.useCtrlKeys": true,
	"vim.hlsearch": true,
	"vim.insertModeKeyBindings": [
		{
			"before": ["j", "j"],
			"after": ["<Esc>"]
		}
	],
	"vim.normalModeKeyBindingsNonRecursive": [
		{
			"before": ["<leader>", "d"],
			"after": ["d", "d"]
		},
		{
			"before": ["<C-n>"],
			"after": [],
			"commands": [
				{
					"command": ":nohl"
				}
			]
		},
		{
			"before": ["<leader>", "o"],
			"after": ["o", "<Esc>", "k"]
		},
		{
			"before": ["g", "C-a"],
			"commands": ["progressive.incrementBy1"]
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
	"workbench.editor.showTabs": "multiple",
	"editor.acceptSuggestionOnEnter": "smart",
	"editor.snippetSuggestions": "top",
	"editor.suggestOnTriggerCharacters": false,
	"editor.suggestSelection": "first",
	// "php-cs-fixer.onsave": true,
	"php-cs-fixer.executablePath": "${extensionPath}/php-cs-fixer.phar",
	"php-cs-fixer.lastDownload": 1627552673014,
	"php-cs-fixer.config": "/home/jpgrefaldo/.vscode/.php_cs",
	"gitlens.hovers.currentLine.over": "line",
	"diffEditor.ignoreTrimWhitespace": false,
	"window.titleBarStyle": "native",
	"gitlens.views.fileHistory.focus": true,
	"gitlens.views.lineHistory.focus": true,
	"editor.smoothScrolling": true,
	// The direct answer to this question is (from this github page):
	// Add this to settings.json (ctrl + , or cmd + ,)
	"editor.tokenColorCustomizations": {
		"textMateRules": [
			{
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
	"intelephense.files.maxSize": 1e34,
	"editor.insertSpaces": false,
	"editor.maxTokenizationLineLength": 200000,
	"typescript.disableAutomaticTypeAcquisition": true,
	"terminal.external.osxExec": "iTerm.app",
	"gitlens.views.repositories.files.layout": "list",
	"files.maxMemoryForLargeFilesMB": 114096,
	"files.watcherExclude": {
		"**/production.js": true,
		"**/production.min.js": true,
		"**/vendor": true,
		"**/public/js": true
	},
	"workbench.fontAliasing": "antialiased",
	"explorer.confirmDelete": false,
	"javascript.updateImportsOnFileMove.enabled": "always",
	"colorize.include": ["colorize.languages"],
	"colorize.languages": ["javascript", "typescript"],
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
	"terminal.integrated.defaultProfile.osx": "zsh",
	"terminal.integrated.allowChords": false,
	"svg.preview.mode": "svg",
	"editor.cursorStyle": "line",
	"editor.lineNumbers": "on",
	"editor.wordSeparators": "/\\()\"':,.;<>~!@#$%^&*|+=[]{}`?-",
	"editor.wordWrap": "off",
	"workbench.editorAssociations": {
		"*.ipynb": "jupyter-notebook",
		"*.0~JLgXah2GJEtZHW2EPtZd60hBLKXhwPb_VC3Gziab8jSTD5b10QR6v711FEQuLxRtRZdBgmHN-cwJfkDzWEzGdg==": "default",
		"*.mobileprovision": "default",
		"git-rebase-todo": "gitlens.rebase"
	},
	"notebook.cellToolbarLocation": {
		"default": "right",
		"jupyter-notebook": "left"
	},
	"editor.inlineSuggest.enabled": true,
	"github.copilot.enable": {
		"*": true,
		"plaintext": true,
		"markdown": false,
		"scminput": false,
		"yaml": false,
		"typescript": false
	},
	"[jsonc]": {
		// "editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"editor.unicodeHighlight.ambiguousCharacters": false,
	"json.maxItemsComputed": 50000,
	"typescript.updateImportsOnFileMove.enabled": "always",
	"settingsSync.ignoredSettings": ["editor.fontFamily"],
	"gitlens.sortBranchesBy": "name:asc",
	"gitlens.views.branches.files.layout": "tree",
	"typescript.tsc.autoDetect": "off",
	"workbench.editor.enablePreview": false,
	"git.mergeEditor": false,
	"task.allowAutomaticTasks": "off",
	"editor.foldingMaximumRegions": 50000,
	"normanstypczynski.gqlformatter.enable.graphql": true,
	"markdownlint.config": {
		"default": true,
		"MD033": false
	},
	"editor.unicodeHighlight.invisibleCharacters": false,
	"[vue]": {
		"editor.defaultFormatter": "octref.vetur"
	},
	"[php]": {
		"editor.defaultFormatter": "junstyle.php-cs-fixer"
	},
	"[javascript]": {
		"editor.defaultFormatter": "svipas.prettier-plus"
	},
	"[typescript]": {
		"editor.defaultFormatter": "vscode.typescript-language-features"
	},
	"[html]": {
		"editor.defaultFormatter": "svipas.prettier-plus"
	},
	"[typescriptreact]": {
		"editor.defaultFormatter": "vscode.typescript-language-features"
	},
	"gitlens.currentLine.uncommittedChangesFormat": "✏️${author} ${ago} ${ • message|50?}",
	"gitlens.graph.dateFormat": null,
	"git-graph.commitDetailsView.fileView.type": "File List",
	"git-graph.customBranchGlobPatterns": [],
	"intelephense.environment.phpVersion": "5.6",
	"gitlens.views.formats.commits.description": "${author, } ${date}",
	"terminal.integrated.gpuAcceleration": "on",
	"redhat.telemetry.enabled": true,
	"team.showWelcomeMessage": false,
	"git.openRepositoryInParentFolders": "never",
	"workbench.activityBar.location": "hidden",
	"[python]": {
		"editor.defaultFormatter": "ms-python.black-formatter"
	},
	"prettier.printWidth": 140,
	"prettier.singleQuote": true,
	"prettier.parser": "typescript",
	"prettier.configPath": ".prettierrc.js",
	"prettier.trailingComma": "all",
	"prettier.prettierPath": "node_modules/prettier",
	"prettier.requireConfig": true,
	"prettier.bracketSameLine": true,
	"prettier.resolveGlobalModules": true,
	"prettier.singleAttributePerLine": true,
	"editor.defaultFormatter": "dbaeumer.vscode-eslint",
	"prettier.tabWidth": 0,
	"prettier.useTabs": true,
	"prettier.enable": false,
	"window.commandCenter": false,
	"workbench.layoutControl.enabled": false,
	"github.copilot.advanced": {
		"inlineSuggestCount": 5,
		"length": 700,
		"listCount": 15,
		"stops": {
		}
	},
	"[ruby]": {
		"editor.defaultFormatter": "svipas.prettier-plus"
	},
	"editor.formatOnSave": true,
	"editor.formatOnSaveMode": "modifications",
	"github.copilot.editor.enableAutoCompletions": true,
	"scm.showChangesSummary": false,
	"scm.showOutgoingChanges": "never",
	"[xml]": {
		"editor.defaultFormatter": "svipas.prettier-plus"
	},
	"github.copilot.nextEditSuggestions.enabled": true
}
