# Media choices and structural deliverables

## Ask before filling visual slots

For each distinct visual need, identify the section, what the visual must communicate, and whether an image is actually necessary. Group similar needs so the user can choose a project-wide policy or a few exceptions.

Example question:

> برای این بخش، عکس محصول کمک می‌کند کاربر ظاهر کالا را بشناسد. ترجیح می‌دهی خودت عکس بدهی، من تصویر مناسب پیدا کنم، از لینک خارجی استفاده کنیم، یا چیدمان و عنصر دیگری انتخاب کنیم؟

Offer generation as another option when appropriate. If the user chooses not to use photos, clarify whether illustrations are acceptable rather than assuming that no photos means permission for any generated visual.

Record the choice and its scope. “خودت تصاویر مناسب پیدا کن” authorizes sourcing within that scope; it does not automatically authorize a different medium or a new visual direction. Do not repeatedly seek consent already given. A concrete request to generate an image is sufficient authorization for that image.

## Routes

| Route | Required behavior |
| --- | --- |
| User supplies assets | Request the relevant images/files in normal chat; explain subject and useful crop/shape. Use assets accurately and respect meaningful details |
| Agent selects existing images | Search only after that route is chosen. Inspect relevance and actual image content, record the source and applicable usage conditions |
| External image URLs | Obtain permission for external image loading. Use direct, verified image URLs with appropriate usage rights, reserved dimensions, and a useful fallback. Do not guess stock-photo IDs or use random-photo endpoints |
| Generated visuals | Use the image-generation capability under its instructions after the user chooses this route. Distinguish conceptual imagery from accurate product documentation |
| Non-image element | Agree on an alternative such as a real product component, diagram, comparison, meaningful typography, interactive demonstration, or Canvas composition |
| Different composition/section | Preserve the original user need or explain why a different section better serves the journey; do not replace useful product information with decorative filler |

Never use unrelated stock photos as product photos. Do not invent a customer's face, testimonial, product specification, or endorsement to make a section look complete. Existing user assets remain the preferred source when accurate and authorized.

Do not silently embed an image from a design-reference site. Research and asset acquisition serve different purposes. If an asset cannot be used reliably or appropriately, explain and offer an alternative within the user's chosen policy.

## No-image alternatives

Explain one or two options suited to the section rather than dumping a list of effects:

- Product explanation: a meaningful comparison, feature anatomy, or actual interactive component.
- Process: a clear journey or sequence with relevant labels.
- Brand introduction: a distinctive typographic composition grounded in the message.
- Data: an accessible chart based on real or clearly identified sample data.
- Atmospheric/expressive visual: a purposeful HTML Canvas composition if the user chooses it.
- Discovery: a functional selector, category navigation, or guided choice.

Canvas is an optional medium, not an automatic substitute for photography. Keep essential text and controls accessible outside the drawing surface, provide a static/text alternative where needed, and respect reduced motion. Do not add constant animation merely to fill space. Clarify whether “canvas” means an HTML Canvas element or a static illustration only when the distinction matters.

## Export the structure

The default structural package is:

1. `page-structure.md`: page tree and section outline with each section's job, primary content, action, information hierarchy, visual/media decision, and responsive behavior.
2. `wireframe.html`: a lightweight neutral layout of the complete requested scope, with representative text lengths, navigation, key controls, and desktop/mobile composition.

Use meaningful labels instead of a screen of anonymous gray boxes. Mark provisional visual slots as wireframe placeholders. Do not fetch or generate imagery just to decorate a structural preview. Include existing page relationships for context, but do not build out-of-scope pages.

If the user wants only a skeleton, deliver it and stop. If they request approval before further design, present the concrete artifacts and wait. If they ask for a structure export alongside implementation, provide both without creating an unrequested approval pause.
