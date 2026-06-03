backend:
  name: git-gateway
  branch: main

media_folder: "EVCC Website/assets/images/uploads"
public_folder: "/assets/images/uploads"

collections:
  - name: "news"
    label: "News & Announcements"
    folder: "EVCC Website/content/news"
    create: true
    slug: "{{year}}-{{month}}-{{day}}-{{slug}}"
    fields:
      - {label: "Title", name: "title", widget: "string"}
      - {label: "Date", name: "date", widget: "datetime"}
      - {label: "Category", name: "category", widget: "string", default: "News"}
      - {label: "Image", name: "image", widget: "image", required: false}
      - {label: "Body", name: "body", widget: "markdown"}

  - name: "events"
    label: "Events"
    folder: "EVCC Website/content/events"
    create: true
    slug: "{{year}}-{{month}}-{{day}}-{{slug}}"
    fields:
      - {label: "Event Title", name: "title", widget: "string"}
      - {label: "Event Date", name: "date", widget: "datetime"}
      - {label: "Location", name: "location", widget: "string", required: false}
      - {label: "Image", name: "image", widget: "image", required: false}
      - {label: "Description", name: "body", widget: "markdown"}

  - name: "gallery"
    label: "Campus Gallery"
    folder: "EVCC Website/content/gallery"
    create: true
    slug: "{{slug}}"
    fields:
      - {label: "Title", name: "title", widget: "string"}
      - {label: "Image", name: "image", widget: "image"}
      - {label: "Description", name: "description", widget: "text"}
