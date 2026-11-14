<a href="https://miljan94.com/"><img src="media/cover.jpg" alt="Auto Servis Miljan94, home page on a laptop and a phone" width="100%"></a>

# Auto Servis Miljan94

A 24-page site for a French car repair shop near Leskovac, with a car that comes apart on the home page as you scroll.

**[miljan94.com](https://miljan94.com/)** · [Case study (in Serbian)](https://svilenkovic.rs/radovi/miljan94) · [Srpski](README.sr.md)

> [!NOTE]
> Client project. The source code belongs to the client and stays in a private repository. This page describes what I built and how.

<table>
  <tr><td><b>Client</b></td><td>Auto Servis Miljan94</td></tr>
  <tr><td><b>Industry</b></td><td>Repairs for Renault and other French cars, and used parts on request</td></tr>
  <tr><td><b>Location</b></td><td>Leskovac, Serbia</td></tr>
  <tr><td><b>Type</b></td><td>Multi-page website</td></tr>
  <tr><td><b>My role</b></td><td>Design, development, SEO and hosting</td></tr>
  <tr><td><b>Stack</b></td><td>Astro 7, TypeScript, Canvas, nginx, JSON-LD</td></tr>
</table>

## About the project

Auto Servis Miljan94 is a repair shop in Gornje Sinkovce near Leskovac. It works mostly on Renault, and also on Peugeot, Citroën and Dacia, from diagnostics and servicing to engine, clutch and gearbox repairs, and now and then it has used parts from dismantled cars. Everything is arranged by phone, so the site had to explain the work clearly and make calling easy, without promising parts in stock or prices up front.

I built the home page around a car that comes apart as you scroll: the bonnet and a wheel move away, the engine, clutch and brake come into view, and at the end the car goes back together. The motion follows ordinary scrolling in both directions, with 144 frames on desktop and 72 lighter ones on phones, and it stays a still image when the system asks for reduced motion or data saver is on. The shop had no photos of its own work yet, so the cars and parts are illustrations. The large image at the top of each page carries an illustrative image label, and the privacy page says that none of them show the workshop or finished jobs.

## What I built

- 24 pages: one for each of eight services and four car makes, plus guides for drivers, used parts, contact and privacy
- A scroll-driven car drawn on canvas, with frames loaded gradually around the point the visitor has reached
- A used parts page with no catalog, explaining what to send so availability can be checked
- Call and SMS buttons on every page instead of a form, with a call and SMS bar at the bottom on phones
- Structured data for the repair shop and each service, with no prices or ratings
- Checks of every page, link, image and the sitemap before each release

## Results

| | Performance | Accessibility | Best practices | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Mobile | 100 | 100 | 100 | 100 |
| Desktop | 100 | 100 | 100 | 100 |

PageSpeed Insights, lab test of the live site, November 2026. Security headers: 6 of 6. Structured data: `AutoRepair`, `Person`.

## Screenshots

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Auto Servis Miljan94, home page on a 1440 px screen"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Auto Servis Miljan94, home page on a phone"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="Used parts: the availability of each part is checked on request, with call and SMS buttons">
<sub>Used parts: the availability of each part is checked on request, with call and SMS buttons</sub>

<img src="media/inner-2.webp" alt="Renault service near Leskovac: one of the four pages by car make">
<sub>Renault service near Leskovac: one of the four pages by car make</sub>

---

<sub>Built by [D. Svilenković](https://svilenkovic.com).</sub>
