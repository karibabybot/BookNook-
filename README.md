# BookNook

A small bookstore site hosted on GitHub Pages. Payments go through one PayPal button.

## Files

- `index.html` - the storefront (design, search, categories, checkout pop-up)
- `books.json` - the list of books. This is the file you edit.
- `add-book.html` - a form that writes the `books.json` text for you
- Site address: https://karibabybot.github.io/BookNook-/
- Add-a-book form: https://karibabybot.github.io/BookNook-/add-book.html

## Add a book

1. Open the add-a-book form, fill it in, and click **Add to list**.
2. Click **Copy list**, then **Open book list on GitHub**.
3. Select everything in the editor, paste, and click **Commit changes**.

The site updates in about a minute. Each book needs: `title`, `author`, `category`. Optional: `year`, `description`, `bestseller` (true/false), `cover` (image file name), `price` (display only).

- **Recently Added** shows the newest books by the `added` date.
- **Best Sellers** shows books with `"bestseller": true`.
- New categories appear automatically when you use a new `category` name.

## Payments

Every book uses the same PayPal button (`PAYPAL_BUTTON_ID` near the top of the script in `index.html`). PayPal charges whatever price that button is set to ($5.00). The price shown on the page is only a label, so keep the two matching.

## Before listing a book

Only list books you have actually prepared as ebooks, and confirm each is public domain where you sell. Do not put the ebook files in this repository: it is public, so anyone could download them.
