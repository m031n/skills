# Source-sheet register and refresh protocol

The requested source sheets are the canonical place for the product's current microcopy and option-specific copy. Read the relevant sheet when access is available, reconcile its terminology with the user request, and treat the latest approved row as stronger evidence than a generic example.

## Registered sources

- UX Writing / current microcopies: https://docs.google.com/spreadsheets/d/1yi_lCHoMjvjVPxt7KqvEkiUSzJdm-ABlARXu-V-XMS8w/edit?gid=0#gid=0
- UX Writing for Option sheets: https://docs.google.com/spreadsheets/d/1143GpIM-1PrexgUX31gvBVlhGdJpRgAa/edit?gid=2127938544#gid=2127938544
- UX Writing - HELIUM: https://docs.google.com/spreadsheets/d/1mDyK9Gs7WDze0imVm0OEFmy5JNNVhg0_GtFm7NfyA80/edit?gid=0#gid=0

Current access status: the first URL still returns `404 NOT_FOUND` from Google Sheets/Drive, and a Drive search by its ID returned no result. Do not claim to have read it unless a later run can inspect or export it. The second URL is now readable through Google Drive as the Excel workbook `UX Writing - Option.xlsx`; it is not a native Google Sheet, so use Drive fetch for read-only inspection rather than Sheets metadata/range tools.

## Verified rules from the Option workbook

- When directly addressing a user by name, use «[نام کاربر] عزیز».
- Put symbols, industries, funds, and other proper names in Persian quotation marks, such as نماد «کتوسعه» and صندوق «لبخند».
- Use readable mathematical digits and Persian units: «۱۰۰ میلیون ریال»، «۵۰ هزار واحد»، «۱۰۰۰ تومان».
- Prefer Persian words; retain English only for proper names or terms without an established Persian equivalent.
- Avoid unnecessary adverbs in product text and tests, including «با موفقیت» and «متأسفانه» when they add no useful information.

The workbook contains working sections for:

- empty states, with location/title/body/actions and checks for user benefit, current state, next state, correctness, brand voice, and terminology consistency;
- dialogs, with direct questions, clear button outcomes, consequences, correctness, voice, and consistency;
- errors, with error type, practical recovery, proximity to the source of the error, clarification, empathy, correctness, voice, and consistency;
- guides, headings/lists/actions, and tests, including whether key meaning appears early and whether the message is useful in its actual product context.

Its example rows include subscription offers, urgent withdrawal/PiFast, file upload limits, and customer-club points. Treat those values as source-specific examples, not universal trading-product facts.

## Verified rules and content from UX Writing - HELIUM

This native Google Sheet has the tabs `Writing Rules`, `Empty States`, ` Dialouges` (including the leading space and spelling), `Toasts`, `Errors`, `Actions`, and `Guide Messages`.

The current workbook reinforces these rules:

- Direct address uses «نام کاربر + عزیز».
- Symbols, funds, industries, and proper names use Persian quotation marks.
- Numeric copy uses readable digits and Persian units.
- Product copy should prefer Persian terminology and avoid unnecessary English.
- Dialogs must use a clear question, explain consequences, and make each button outcome explicit.
- Empty states should identify the current state, user value, and next action.
- Toasts should lead with the important words and state the concrete result; avoid «با موفقیت انجام شد»، «ثبت گردید»، and similar system language when a direct result is available.
- Error review checks the user's next recovery step, proximity to the source of the error, clarity, and non-blaming empathy.
- Guide messages are checked for brevity, information needed for the next action, consequences of irreversible actions, and optional help for users who need reassurance.

The action vocabulary currently includes «خرید»، «فروش»، «باز»، «انجام‌شده»، «ناموفق»، «همه»، «سبد سهام»، «واریز آنی وجه»، «ثبت فیش واریز»، «تغییر کارگزار ناظر» and «برداشت وجه». Reuse these terms when the product context matches; do not replace them with stylistic synonyms.

The workbook also contains review flags and inconsistent draft examples. Treat the final/revised copy and explicit review notes as stronger evidence than an unreviewed draft. Examples include replacing «دیده‌بان با موفقیت ساخته شد» with «دیده‌بان «وارن بافت» ساخته شد» and adding quotes around symbols and watchlist names.

When a sheet becomes accessible:

1. Confirm the file and tab, then inspect headers and approved/current-status fields.
2. Prefer bounded reads or an export; preserve RTL text, exact punctuation, and IDs.
3. Extract canonical terms, approved microcopies, tone labels, and option differences.
4. Update the skill's reference only when the user explicitly asks to persist a change; otherwise use the live sheet for that task.
5. If sheet copy conflicts with a direct user instruction, follow the user instruction and flag the conflict.
