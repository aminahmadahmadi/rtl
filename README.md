<div dir="rtl" align="right">
# rtl
راست به چپ کردن وبسایت سرویس‌های خارجی

---

### آموزش استایل برای اپلیکیشن اسلک:

۱- در اپ این کامند را اجرا کنید
`/slackdevtools`

۲- بر روی `<head>` راست کلیک کرده و گزینه `Edit as HTML` را انتخاب کنید

۳- به انتهای باکس برید و قبل از `</head>` متن زیر را paste کنید.

```css
<style type="text/css">
[lang] .p-rich_text_block,.ql-editor, .c-pillow_file__post__content, .c-message_kit__text, .c-dialog, .c-link, input, .c-select, .p-block-kit-select_options,.p-block_kit_renderer__block_wrapper, div.c-message_kit__gutter__right  {line-height:1.7;font-family: "IRANYekan", "Tahoma";text-align: right;direction: rtl;}
b,strong, .c-pillow_file__title {font-family: "IRANYekan ExtraBold", "Tahoma";}
.c-pillow_file__post__content ul>li[data-checked=false]:before, .c-pillow_file__post__content ul>li[data-checked=true]:before {margin-left: 6px;margin-right: 0px;}
.c-mrkdwn__pre ,.ql-code-block,.CodeMirror-code,.c-pillow_file__content{direction: ltr; text-align: left;}
i.c-icon.c-input_text_icon__icon.c-input_text_icon__icon--small.c-icon--clock-o.c-icon--inherit {right:5px}
i.c-icon.c-icon--chevron-medium-down.c-icon--inline {left: -10px}
i.c-icon.c-input_text_icon__icon.c-icon--clock-o.c-icon--inherit{right:10px;}
div.c-message__reply_bar.c-message_kit__thread_replies {direction: ltr;}
.c-message_kit__gutter{direction: rtl;padding-top: 15px;}
.c-message_kit__gutter__left{margin-left: 8px;margin-right: 0;}
.c-message_kit__gutter__right{padding-right: 10px !important;}
.slack-list-item-checkbox{margin-right: 0; margin-left: 6px;}
</style>
```

۴- با کلیک خارج از باکس تغییرات را سیو کنید

۵- درصورت بازگشت اسلک به حالت اولیه این مراحل را تکرار کنید

### آموزش استایل برای نسخه وب اسلک:

۱- اکستنشن [stylebot](https://github.com/ankit/stylebot) را نصب کنید.  [مرورگر کروم](https://chrome.google.com/webstore/detail/stylebot/oiaejidbmkiecgbjeifoejpgmdaleoha?hl=en)  |  [مرورگر فایرفاکس](https://addons.mozilla.org/en-US/firefox/addon/stylebot-web/)

۲- با کلیک بر روی شکل اکستنشن گزینه `options...` را باز کنید

۳- از تب `styles` بر روی گزینه `add a new styles` کلیک کنید.

۴- در بخش url لینک زیر را وارد کنید
https://app.slack.com/

۵- و در ادیتور موجود کد زیر را paste کنید

```css
[lang] .p-rich_text_block,.ql-editor, .c-pillow_file__post__content, .c-message_kit__text, .c-dialog, .c-link, input, .c-select, .p-block-kit-select_options,.p-block_kit_renderer__block_wrapper, div.c-message_kit__gutter__right  {line-height:1.7;font-family: "IRANYekan", "Tahoma";text-align: right;direction: rtl;}
b,strong, .c-pillow_file__title {font-family: "IRANYekan ExtraBold", "Tahoma";}
.c-pillow_file__post__content ul>li[data-checked=false]:before, .c-pillow_file__post__content ul>li[data-checked=true]:before {margin-left: 6px;margin-right: 0px;}
.c-mrkdwn__pre ,.ql-code-block,.CodeMirror-code,.c-pillow_file__content{direction: ltr; text-align: left;}
i.c-icon.c-input_text_icon__icon.c-input_text_icon__icon--small.c-icon--clock-o.c-icon--inherit {right:5px}
i.c-icon.c-icon--chevron-medium-down.c-icon--inline {left: -10px}
i.c-icon.c-input_text_icon__icon.c-icon--clock-o.c-icon--inherit{right:10px;}
div.c-message__reply_bar.c-message_kit__thread_replies {direction: ltr;}
.c-message_kit__gutter{direction: rtl;padding-top: 15px;}
.c-message_kit__gutter__left{margin-left: 8px;margin-right: 0;}
.c-message_kit__gutter__right{padding-right: 10px;}
.slack-list-item-checkbox{margin-right: 0; margin-left: 6px;}
```

۶- گزینه save را بزنید و تب اسلک را رفرش کنید.
</div>
