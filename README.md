# Heraless

FileSystem path based express server warpper. Inspired by Next.JS's api.

# Installation

It is easy to install.

1. Clone this repository
2. Run `npm install`, `yarn install`, or etc...
3. Done!

# Usage

`/src/routes` is the directory that you have been seen in Next.JS (/pages/api). export function named as the method that you want. Here is a example below. It support GET, POST, PATH, PUT, and DELETE.

```typescript
export function GET(req: Req, res: Res) {
  res.send("This server is powered by Heraless by @github/Oein");
}

export function POST(req: Req, res: Res) {
  res.send("This server is powered by Heraless by @github/Oein");
}

export function PATCH(req: Req, res: Res) {
  res.send("This server is powered by Heraless by @github/Oein");
}

export function PUT(req: Req, res: Res) {
  res.send("This server is powered by Heraless by @github/Oein");
}
export function DELETE(req: Req, res: Res) {
  res.send("This server is powered by Heraless by @github/Oein");
}
```
