# Gmail signature procedure

Draft interview writing sample for Timothy Frantz. Pending editorial review and live Gmail validation.

## Files

- `create-gmail-signature.rst`: User-facing procedure in reStructuredText.
- `conf.py`: Minimal Sphinx configuration for rendering the procedure.

## Audience and scope

Readers can sign in to Gmail and compose a message but have not configured a signature. The procedure covers the English desktop web interface, a text signature, automatic insertion in new messages, and an optional default for replies and forwards. Mobile configuration, images, and multiple sending addresses are outside this sample's scope.

## Editorial approach

Follow the Microsoft Writing Style Guide: task-oriented headings, numbered actions, input-neutral verbs, bold interface labels, and explicit completion steps. Preserve interface capitalization. Explain the difference between the signature's name and its content. Keep authoring and validation notes outside the user-facing procedure.

## Build

With Python and Sphinx installed, run from this directory:

```sh
python -m sphinx -b html -W --keep-going . _build/html
```

Open `_build/html/create-gmail-signature.html` to review the result. The build command and rendered output have not yet been validated in this draft environment. Before submission, record the tested Sphinx version and pin it in the repository's dependency file.

## Review checklist

- [ ] Follow the procedure in Gmail, starting with no signature configured.
- [ ] Confirm every interface label and capitalization against the live English interface.
- [ ] Confirm the signature name and text box descriptions are clear.
- [ ] Save changes and verify automatic insertion in a new message.
- [ ] Test both choices for replies and forwards.
- [ ] Test the recovery guidance when no default signature is selected.
- [ ] Record the validation date, browser, operating system, and account type.
- [ ] Build with no warnings and inspect the rendered output.
- [ ] Have a second reader follow the procedure without coaching.

## References

Consulted October 20, 2026. Documentation research is complete; live UI validation remains pending.

- [Gmail Help: Create a Gmail signature](https://support.google.com/mail/answer/8395?hl=en)
- [Microsoft Writing Style Guide](https://learn.microsoft.com/en-us/style-guide/welcome/)