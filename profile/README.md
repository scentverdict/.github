<p align="center">
  <a href="https://scentverdict.com">
    <img src="https://scentverdict.com/images/brand/logo.png" alt="ScentVerdict" width="280">
  </a>
</p>

<h3 align="center">The UK's Which? for perfume</h3>

<p align="center">
  Independent, verdict-driven perfume reviews powered by AI.<br>
  No fake reviews. No pay-to-play. Just honest opinions on whether a fragrance is worth your money.
</p>

<p align="center">
  <a href="https://scentverdict.com">Website</a> &middot;
  <a href="https://medium.com/@scentverdict">Medium</a> &middot;
  <a href="https://www.facebook.com/scentverdict">Facebook</a> &middot;
  <a href="https://www.instagram.com/scentverdict">Instagram</a> &middot;
  <a href="https://www.pinterest.co.uk/scentverdict">Pinterest</a>
</p>

---

### What is ScentVerdict?

ScentVerdict is an independent perfume review and discovery platform. Every perfume gets an editorial verdict - **Favourite**, **Statement**, or **Acquired** - based on quality, value, and wearability. We use AI to analyse scent profiles, match dupes, and generate unique visualisations called **ScentArt** that bring each fragrance to life on screen.

### Features

- **1,400+ perfume verdicts** with detailed scent breakdowns
- **AI dupe matching** - find affordable alternatives to designer fragrances
- **ScentArt** - unique visual representations of how a perfume smells
- **Side-by-side comparisons** - head-to-head breakdowns to help you choose
- **UK prices** from trusted retailers with price-per-ml analysis

### Built With

**Framework & Backend**
- [.NET 10](https://github.com/dotnet/runtime) - Runtime
- [ServiceStack](https://github.com/ServiceStack/ServiceStack) - Web framework, ORM, and API layer
- [Razor Pages](https://github.com/dotnet/aspnetcore) + [HTMX](https://github.com/bigskysoftware/htmx) - Server-rendered pages with dynamic interactions
- [PostgreSQL](https://www.postgresql.org/) + [Npgsql](https://github.com/npgsql/npgsql) - Database and .NET data provider

**AI & Content**
- [Anthropic Claude](https://www.anthropic.com/) - Verdicts, descriptions, dupe analysis, and scent matching
- [Markdig](https://github.com/xoofx/markdig) - Markdown processing
- [Jint](https://github.com/sebastienros/jint) - JavaScript interpreter for .NET

**ScentArt & Images**
- [@napi-rs/canvas](https://github.com/napi-rs/canvas) - Server-side perfume visualisation rendering
- [ImageSharp](https://github.com/SixLabors/ImageSharp) - Image processing

**Infrastructure & Ops**
- [DigitalOcean](https://www.digitalocean.com/) - Hosting and CDN
- [Serilog](https://github.com/serilog/serilog) + [Seq](https://github.com/datalust/seq-app) - Structured logging
- [Polly](https://github.com/App-vNext/Polly) - Resilience and fault handling

**CLI & Tooling**
- [Spectre.Console](https://github.com/spectreconsole/spectre.console) - Rich console UI
- [System.CommandLine](https://github.com/dotnet/command-line-api) - CLI argument parsing
- [Omnara](https://omnara.com/) - AI coding agent command centre

**Testing**
- [xUnit](https://github.com/xunit/xunit) - Unit and integration testing
- [Playwright](https://github.com/microsoft/playwright) - Browser automation and screenshots
- [BenchmarkDotNet](https://github.com/dotnet/BenchmarkDotNet) - Performance benchmarking
