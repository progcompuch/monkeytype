Be extremely concise. Sacrifice grammar for concision.
Frontend is partially migrated from vanilla JS to SolidJS — new components use `.tsx`, legacy code remains vanilla.
Single test file: `pnpm vitest run path/to/test.ts`
When running oxc lint, always use `--format agent`.
For typechecking, use `pnpm oxlint --type-aware --type-check` instead of `tsc`.
For styling, use Tailwind CSS, class property, `cn` utility. Do not use classlist. Only colors available are those defined in Tailwind config.
In legacy code, use `i` tags with FontAwesome classes. In new code, use `Fa` component.
In plan mode, before writing up a plan, ask clarifying questions if needed. At the end of plan mode, give me a list of unresolved questions to answer, if any. Make them concise.
This is progcompea type: fork of monkeytypegame/monkeytype (remote `origin`, branch `master`), lives at progcompuch/monkeytype (remote `progcompuch`, branch `main`).
Commit subjects end with author GitHub handle, like upstream: `feat: add x (@handle)`.
Release notes: progcompea changes (commits in `git log origin/master..HEAD`) go in their own list, separate from upstream-merged changes, each credited `(@handle)` like upstream. See docs/CONTRIBUTING.md#release-notes.
