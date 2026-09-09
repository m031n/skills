# Trading microcopy patterns

Use these as patterns, not a blind phrase bank. Replace bracketed values only with supplied, verified values.

## Orders

- Buy: «خرید [نام نماد]»
- Sell: «فروش [نام نماد]»
- Submit: «ثبت سفارش خرید» / «ثبت سفارش فروش»
- Pending: «سفارش شما در انتظار اجراست.»
- Executed: «سفارش شما اجرا شد.»
- Rejected: «سفارش ثبت نشد. [دلیل واقعی یا اقدام بعدی].»
- Cancel: «لغو سفارش»

For order confirmations, include the exact action and supplied context. A safe title shape is «آیا از ارسال فروش «[نماد]» با [مشخصات] اطمینان دارید؟». Do not shorten it to an ambiguous action-only question.

## Money and account

- Insufficient balance: «موجودی حساب کافی نیست. ابتدا حساب خود را شارژ کنید.»
- Successful deposit: «مبلغ [مقدار] به حساب شما اضافه شد.»
- Failed payment: «پرداخت انجام نشد. [اقدام واقعی].»
- Pending review: «اطلاعات شما در حال بررسی است.»

Never add a fee, deadline, settlement date, limit, or processing time unless the input provides it.

## Empty and history states

Use progressive disclosure on dense mobile screens: teaser → up to three recent transactions → full-history action. Keep the primary buy/sell actions reachable. Useful labels include «مشاهده تاریخچه معاملات» and «هنوز سفارش فعالی ندارید. با ثبت سفارش جدید، شروع کنید.»

## Dialogs and toasts

Dialogs should make the question, consequence, and button outcome explicit. For example: «آیا از درخواست برداشت وجه به روش پی‌فست اطمینان دارید؟ پس از ثبت درخواست، امکان لغو درخواست برداشت وجه وجود ندارد.» with actions «ثبت درخواست» and «انصراف».

For result toasts, lead with the concrete object and result: «نماد «خساپا» به دیده‌بان «تست» اضافه شد.» or «فیش واریز شما لغو شد.» Avoid generic success phrasing such as «با موفقیت انجام شد» and replace system verbs such as «ثبت گردید» with direct verbs such as «ثبت شد».

When auditing copy, check whether important terms appear early, whether the message is useful in the moment, whether it matches the surface, and whether the result preserves canonical names and symbols.

## Spreadsheet review schema

When reviewing or producing a UX-writing sheet, preserve these fields where present: location, title, body, actions, user-first check, current-state check, next-state check, correctness, brand voice, and terminology consistency. Do not silently collapse distinct states or overwrite approved copy; mark alternatives and unresolved assumptions.
