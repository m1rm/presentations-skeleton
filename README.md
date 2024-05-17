# Presentations
This repo holds a simple setup to create presentations
using [Marp](https://marp.app/).

## Prerequisites
- pnpm
- just
- git
- fish
- xdg-open
- findutils
- oxipng
- jpegoptim

## How it works
In the `src` folder you need to have subfolders. Each subfolder holds **one** `index.md`. The subfolder's **name** corresponds to the name of the generated PDF. Each generated PDF can be found in the `dist` folder.

## Setup
1. `cd src`

2. Install dependencies:
`just install`

3. `cd example`

4. Build the empty example.pdf: `just build`

## Assets
Assets are placed in the subfolders next to the index.md.
pngs and jpegs can be optimized using `just optimize`.

## Special Thanks
[Pierre Schmitz](https://github.com/pierres)