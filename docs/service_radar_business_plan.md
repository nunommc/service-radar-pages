# Service Radar / Frontdesk (code name)
## Business Plan and Presentation Strategy

**Working draft | 3 November 2026**
**Purpose:** Turn the original pitch outline and the expanded product ideas into a decision-ready business plan and a source document for a new investor / partner presentation.

> **Working thesis**
> Service Radar should become the operating layer between local service demand and service providers: discover, book, collect payment, protect revenue, recover empty slots, and optimise the provider's working day. The consumer marketplace is the demand surface; Frontdesk is the provider-facing intelligence and automation layer.

**Status of this document:** The original slides are treated as source material. New product recommendations, price points, market sequencing and financial scenarios are proposals to validate, not facts about an existing product or traction.

---

# 1. Executive summary

Service Radar began with a straightforward problem: people, especially travellers, expats and newcomers, struggle to discover and book local services when they do not speak the local language or know the local market. The original pitch proposed location-based discovery, flexible booking, online payments and invoicing, and an influencer / creator reward system.

The expanded concept is more valuable and more defensible. Service Radar can help providers earn more from the capacity they already have, while reducing the operational work involved in answering enquiries, taking bookings, collecting money, handling cancellations and travelling between appointments.

The product should be designed as two connected businesses:

1. **Customer marketplace:** a multilingual way to find, compare and book a trusted local service, by location, service area, availability, price and customer preference.
2. **Provider operating system:** booking management, deposits and payments, cancellation recovery, customer rebooking, analytics, and, for mobile professionals, travel-time-aware route optimisation. A premium AI Frontdesk handles conversations and routine booking work across web, messaging and phone.

The main strategic recommendation is to avoid launching as a generic directory for every type of local service. Start with a narrow supply segment and a compact geographic cluster where the operational advantage can be measured. The strongest initial wedge is **mobile beauty and wellness professionals** who travel to customers, such as massage therapists, nail technicians and personal trainers. In parallel, a small cohort of fixed-location salons can validate cancellation recovery and revenue management. Healthcare-led categories such as dentistry and physiotherapy should follow only after a deliberate privacy and regulatory review.

The most compelling differentiator is not an AI chatbot by itself. Existing competitors already offer booking, deposits, waitlists, payments and, in some cases, AI reception. The opportunity is to connect these workflows into a measurable revenue and utilisation engine, especially for providers who travel between customers.

**Recommended direction**

- Keep **Service Radar** as the working marketplace / umbrella name for now.
- Use **Frontdesk** as the premium AI assistant and provider-automation product, or as the product descriptor if the brand changes.
- Pilot in one city-cluster and one or two service categories before opening three countries at once. The Bieruń-Tychy-Mikołów example is a useful prototype geography for mobile routing, subject to validating provider density and customer demand.
- Evaluate **Adyen for Platforms** first for a unified marketplace payment model across Portugal, Poland and the UK. Keep Stripe Connect, PayU Marketplace and Mollie Connect in the evaluation set. The choice depends on seller eligibility, local payment methods, commercial terms, payout timing and liability allocation.
- Do not build native crypto custody or balances into the first release. Consider crypto only later through a regulated payment partner with conversion to local fiat.
- Test a subscription-plus-commission model. The subscription lowers the commission rate; the highest tier includes AI Frontdesk and smart route optimisation, with a tightly capped trial to demonstrate ROI.

**What needs to be proved before scaling**

1. Providers will adopt the platform and route meaningful booking volume through it.
2. Customers accept the payment and deposit policy without materially reducing conversion.
3. Cancellation recovery produces incremental completed revenue, not just discounted bookings that would have happened anyway.
4. Route optimisation reduces travel time / distance without creating unacceptable appointment changes or customer friction.
5. The payment provider can onboard the actual provider population, including sole traders and mobile self-employed professionals, in each launch country.

# 2. What the original pitch already established

The supplied slide text contains these original elements:

- **Problem:** language barriers make local services harder to access for travellers and newcomers; booking salons and therapists is already inconvenient.
- **Solution:** payments and invoicing; location-based booking across diverse services; flexible scheduling from same-day to 45 days ahead.
- **Target users:** local residents, travellers / tourists, and expats / newcomers.
- **Original uniqueness claims:** search within a radius and a reward system for influencers / content creators to encourage organic promotion.
- **Competition named:** Service Radar, HeyGoldie.com, Buk.pt and Google Calendar.
- **Team named:** Nuno Costa (Founder and CTO), Luis Damião (CEO), Tiago Quintans (CMO).
- **Uncompleted slides:** actual product status, next goals, ask / closing visual and contact details.

The original competitor comparison contains three checkmarks / crosses per competitor, but the text extraction does not preserve the column headings. Those symbols cannot safely be translated into specific feature claims.

The original presentation does not provide traction, customer interviews, provider counts, booking volume, revenue, funding requirement, product readiness, a cost base or a financial forecast. These must not be invented for the new deck. The business plan below proposes how to gather and present that evidence.

# 3. The problem to solve

## 3.1 Customer-side problems

- **Discovery friction:** a customer may not know which provider is reputable, available or suitable nearby.
- **Language friction:** service descriptions, cancellation terms, questions and appointment instructions may be in a language the customer does not understand.
- **Availability friction:** customers often message several businesses and wait for replies instead of seeing bookable availability immediately.
- **Payment friction:** payment methods vary by country. Some customers want a deposit; others expect to pay online or with familiar local methods.
- **Trust friction:** customers need transparent pricing, provider identity, reviews, service location and clear cancellation rules.

## 3.2 Provider-side problems

- **Interrupted work:** phone calls, WhatsApp messages, social messages and email enquiries interrupt the actual service being delivered.
- **Empty capacity:** cancellations and no-shows create slots that are difficult to refill at short notice.
- **Poor booking conversion visibility:** providers often cannot see how many potential customers abandoned the booking process, or at which step.
- **Payment administration:** deposits, balances, refunds, invoices and reconciliation consume time.
- **Under-utilised customer history:** providers know that customers return, but may not have an effective, consent-based way to prompt rebooking at the right time.
- **Travel inefficiency:** mobile providers can lose a large part of their day driving between geographically scattered customers.
- **Fragmented tools:** calendar, payment terminal, messages, customer list and route planning may be separate systems.

## 3.3 The economic problem

The platform should focus on four measurable forms of value:

1. **More completed bookings** from customers who would otherwise abandon or fail to find a provider.
2. **More revenue per available hour** by filling cancellations and improving schedule density.
3. **Less non-billable time** spent on calls, messages, payment handling and travel.
4. **Lower revenue leakage** from no-shows, late cancellations and unpaid balances.

These are the outcomes to sell. “AI-powered” is a product mechanism, not the customer promise.

# 4. Product vision and positioning

## 4.1 Proposed positioning

**For customers:** Find and book the right local service, in your language, at a time and place that works for you.

**For providers:** Turn more enquiries into paid appointments, recover cancelled slots automatically, and spend less time managing the diary.

**For mobile professionals:** A smarter day plan that reduces unnecessary travel while respecting customer availability and provider rules.

A concise positioning line for a future deck:

> **The intelligent front desk for local services: more bookings, fewer empty slots, less admin and smarter routes.**

## 4.2 Two-sided product architecture

| Product surface | Primary user | Core value |
|---|---|---|
| Service Radar discovery | Consumer | Search and compare nearby services, including providers who travel to the customer |
| Booking and checkout | Consumer + provider | Live availability, clear policies, deposits / prepayment and confirmation |
| Provider workspace | Provider | Calendar, customers, services, payments, payouts and performance reporting |
| Revenue Recovery | Provider | Waitlist, cancellation offers, rebooking prompts and configurable discounts |
| AI Frontdesk | Provider + consumer | Answers enquiries and completes routine booking actions across channels |
| Route Optimiser | Mobile provider | Reorders flexible appointments to reduce drive time and improve capacity |

The marketplace should not be the only way providers use the product. A provider must be able to use the booking widget and provider workspace with customers who arrive from their own website or social channels. Marketplace discovery can then become an incremental acquisition channel.

# 5. Target markets and initial customer segments

## 5.1 Supply-side segments

| Segment | Typical needs | Product value |
|---|---|---|
| Solo fixed-location professional | Online booking, deposits, reminders, cancellations, repeat customers | Simple calendar, checkout and cancellation recovery |
| Mobile / at-home professional | All of the above plus travel area, travel time, buffers and route sequencing | Route optimisation and flexible appointment windows |
| Small salon / studio team | Staff calendars, services, rooms / equipment, payments and team reporting | Shared calendar, permissions, team utilisation and AI reception |
| Multi-location business | Central reporting, location-level calendars, staff access and brand control | Multi-location management and consolidated analytics |

## 5.2 Demand-side segments

Retain the three groups from the original deck:

- Local residents looking for convenient and reliable local services.
- Travellers and tourists seeking immediate access to local services.
- Expats and newcomers navigating unfamiliar environments.

Add two behavioural groups for product design:

- **Time-sensitive customers:** need a service soon and are willing to consider a nearby alternative.
- **Flexible customers:** can move within a specified time window in exchange for a better price or a more convenient appointment.

Flexibility is strategically valuable because it creates the option to optimise provider routes and fill otherwise-unused capacity.

## 5.3 Recommended launch wedge

Start with **mobile beauty and wellness services** in one dense local cluster. Examples include massage, nails / beauty services at home and personal training. This segment makes the route-optimisation idea tangible and avoids immediately taking on the data sensitivity of healthcare scheduling.

Run a parallel but limited test with fixed-location salons to validate cancellation recovery, deposits and repeat booking. Do not try to launch every service category at once.

The Bieruń-Tychy-Mikołów example can be used to design and test a small route-optimisation pilot. It is not evidence of market size or provider density; those must be measured through actual recruitment.

## 5.4 Categories to delay

Dentistry, medical services and services that require detailed health information can be attractive later, but they introduce higher sensitivity around appointment data, intake forms and customer notes. Health data is a GDPR special category and receives additional protection. [13] Start with lower-sensitivity services and expand only after a privacy impact assessment and country-specific review.

# 6. Product modules and key workflows

## 6.1 Discovery and trust

- Search by service category, location, date / time and provider availability.
- Search by radius in kilometres or, preferably for mobile services, by estimated travel time.
- Show whether a provider works at a fixed location, travels to the customer or offers both.
- Display transparent service descriptions, duration, price, travel fee, cancellation rules, language support and availability.
- Show verified reviews linked to completed bookings.
- Allow the customer to filter for “available today”, “next available”, “at my address” and “within X minutes”.
- Provide translated service content and booking instructions while preserving the provider's authoritative original wording.

Location search should distinguish two concepts:

1. **Customer search radius:** how far the customer is willing to travel to a fixed provider.
2. **Provider service area:** how far / how long a mobile provider is willing to travel to a customer.

These are not interchangeable settings.

## 6.2 Booking engine

- Provider-defined working hours, service duration, buffers, staff, equipment and blocked time.
- Same-day booking and advance booking, with a configurable booking horizon. The original deck proposed up to 45 days; retain this as a sensible initial default only if provider interviews support it.
- Real-time availability and conflict prevention.
- Customer-selected fixed time or flexible time window.
- Automatic confirmations, reminders, rescheduling and cancellation handling.
- Clear policy display before payment.
- Booking state machine: requested, awaiting payment, confirmed, reschedule proposed, completed, cancelled, no-show, refunded / disputed.

## 6.3 Deposits and prepayment

Providers should choose a payment policy per service, with sensible presets:

- No deposit for low-risk / repeat customers.
- Partial deposit for ordinary bookings.
- Higher deposit or full prepayment for high-value, long-duration or high no-show-risk services.
- A defined balance collection flow if the customer pays only a deposit.

The product should not hard-code one universal percentage. Test different deposit levels by service and provider segment. The platform should make the total price, deposit amount, balance due, cancellation deadline and refund treatment obvious before checkout.

Full online prepayment can remove cash handling and payment follow-up from the service provider, but it also moves more customer-service work to the platform: refund requests, chargebacks, failed payments and payment disputes. The payment contract must explicitly allocate those responsibilities.

## 6.4 Booking funnel and abandonment analytics

Track the funnel at minimum:

1. Search result viewed.
2. Provider / service opened.
3. Service selected.
4. Availability displayed.
5. Time selected.
6. Customer details completed.
7. Deposit / payment terms displayed.
8. Payment initiated.
9. Booking confirmed.

Report conversion and abandonment by step, device, source, language, service, provider and payment policy. This gives the provider evidence of whether a large upfront payment is reducing conversion.

Use precise labels such as “booking started but not completed”. A person who opens a provider page is not necessarily a lost booking. Avoid presenting all funnel exits as confirmed purchase intent.

The platform can run opt-in experiments on deposit percentage, cancellation window and payment method. Measure the trade-off between conversion, no-shows, refunds and completed revenue rather than optimising only for checkout conversion.

## 6.5 Cancellation recovery and yield management

This can become one of the strongest modules for fixed-location providers.

**Illustrative workflow**

- Customer C1 books a two-hour service from 10:00 to 12:00 on day X and pays a 15% deposit.
- C1 cancels three days before the appointment.
- The system identifies two one-hour slots, 10:00-11:00 and 11:00-12:00, that can be sold without breaking the provider's service rules.
- The provider's pre-agreed recovery policy allows the platform to offer those slots at a temporary discount, for example 30%, to a relevant opt-in audience.
- A customer who has never used that provider receives a relevant availability offer, accepts it, pays the required amount and receives confirmation.
- The system updates the provider calendar and payout forecast. The provider does not need to manually search for a replacement customer or negotiate the price.

**Important product rules**

- Do not market third-party offers to customers simply because the platform has their email address. Obtain and retain appropriate permission for marketplace / provider promotions, by channel and purpose. Service notifications and marketing messages must be separated.
- Let providers define minimum price, maximum discount, eligible services, minimum notice and whether automated recovery is allowed.
- Do not discount a slot that is likely to sell at full price. Use time-to-appointment, demand, historical occupancy and price sensitivity carefully.
- Keep a complete audit trail of original booking, cancellation, offer, acceptance, new booking and refunds.
- The provider calendar must reflect the actual confirmed schedule. “No notification” can be a preference; “no visibility” should not be the default. Providers should pre-authorise which changes the system may make automatically.
- Ensure that the customer sees the discounted price, the provider and any restrictions before accepting.

## 6.6 Rebooking and customer lifecycle

Use service history to predict likely return windows. For example, when a customer regularly books a haircut every five weeks, the system could send a reminder or a relevant offer around week four if there is a suitable opening.

Build recommendations from the customer's own booking history and stated preferences, not assumptions about gender or other inferred personal characteristics. Allow customers to manage preferences and opt out of marketing. Use service reminders and marketing offers as distinct message types.

## 6.7 Mobile route optimiser

The route optimiser is a potentially distinctive premium feature, but it must be built as a constrained scheduling and routing engine, not as a free-form chatbot guessing routes.

**Inputs**

- Provider starting point and end-of-day preference.
- Customer locations, service durations and appointment time windows.
- Provider work hours, breaks, buffer times and maximum travel time.
- Service-area policy: radius in km, maximum drive time, or both.
- Traffic-aware travel-time estimates for the expected departure time.
- Skills, equipment and any staff / vehicle constraints.
- Customer flexibility, including the earliest / latest acceptable arrival time.

**Illustrative route**

- C1 in Bieruń books 10:00.
- C2 in Tychy books 14:00.
- C3 in Mikołów books 12:00.
- The current order may force unnecessary travel. If C2 and C3 have opted into flexibility, the system can identify a better sequence and propose an appointment swap or adjusted arrival window.

**Recommended workflow**

1. During booking, ask whether the customer has a fixed time or can accept a window, such as 11:30-13:00.
2. Before the day, calculate route alternatives using time-dependent road travel estimates.
3. Identify the smallest practical group of customers whose schedules could improve the route.
4. Offer each customer one or more acceptable alternatives, with an incentive where appropriate.
5. Hold proposed slots briefly and avoid confirming a partial chain that creates a conflict.
6. Commit the new schedule only when all required customers accept and the provider's pre-authorised rules are satisfied.
7. Update the provider calendar and customer confirmations; log the change.

A provider should be able to set a policy such as: “You may automatically move flexible bookings within the customer's accepted window, provided no service is delayed beyond the confirmed limit and the route improves by at least 15 minutes.” The provider must remain able to override the result.

**Optimisation objective**

Minimise a weighted combination of drive time, distance, idle gaps and late-arrival risk, subject to customer time windows, provider working hours, service duration and contractual constraints. Do not optimise kilometres alone: a short distance through heavy traffic can be slower than a longer road route.

**Service area configuration**

Offer a radius in kilometres for simple configuration, but make maximum estimated travel time the more useful operational constraint. A provider might choose “within 20 km” or “within 25 minutes at expected appointment time”. An isochrone-based area is more realistic than a simple circle, especially during peak traffic.

**Where AI belongs**

- A deterministic optimiser or constraint solver calculates feasible routes and schedule permutations.
- Traffic / routing services supply estimated travel times.
- The AI agent explains proposed changes, asks customers about flexibility and manages the conversation.
- The AI must not invent availability or commit a schedule without passing through the booking engine's rules.

## 6.8 AI Frontdesk

Frontdesk is the premium conversational layer that answers questions and performs approved actions.

**Channels, in recommended order**

1. Website widget / booking page.
2. WhatsApp Business.
3. Inbound phone / voice agent.
4. Telegram or other channels only when there is measured demand.

**Capabilities**

- Answer questions about services, duration, price, location, travel area and availability.
- Recommend an appropriate service based on customer-stated needs.
- Book, reschedule and cancel within provider rules.
- Collect missing information and send secure payment links.
- Explain cancellation terms and deposits.
- Handle common questions in the customer's language.
- Escalate unusual, sensitive or disputed cases to a human.
- Contact flexible customers about approved schedule changes or suitable cancellation openings.

**Guardrails**

- Clearly disclose that the customer is speaking with an AI assistant. EU AI Act transparency requirements for direct AI interactions apply from 2 August 2026. [12]
- Never claim a booking is confirmed until the booking engine confirms it.
- Never change price, policy or appointment windows outside provider settings.
- Provide a human escalation route.
- Do not collect unnecessary health or sensitive information.
- Do not use voice recordings or transcripts for model training by default; set retention and consent rules deliberately.

# 7. Differentiation and defensibility

## 7.1 What is not unique enough on its own

- Online booking.
- Appointment reminders.
- Deposits and no-show prevention.
- A waitlist.
- Customer reviews.
- A booking widget.
- A multilingual chatbot.
- Basic local search.

Competitors already offer combinations of these functions. Booksy promotes marketplace discovery, online booking, deposits and cancellation protections. Fresha combines discovery, booking, payments, waitlists / marketing capabilities and a marketplace. Goldie now promotes AI reception, waitlist, no-show protection and dynamic pricing. BUK in Portugal offers booking for salons, spas, personal trainers, physiotherapists and other appointment businesses. [18]-[21]

## 7.2 Where Service Radar can earn a position

1. **Route-aware booking for mobile providers:** customers can select flexible windows and the system improves the provider's day across multiple appointments.
2. **Closed-loop cancellation recovery:** cancelled capacity is automatically marketed, rebooked and reflected in the provider's calendar and payment forecast.
3. **Conversion intelligence:** providers can see how deposit and prepayment settings affect booking completion, not just total appointments.
4. **Multilingual front desk:** the customer can ask questions and complete the booking in their preferred language while the provider controls the source information and policy.
5. **One operational workflow:** discovery, booking, payment, refund, reschedule, recovery, route and payout data are connected.

The defensibility comes from local supply density, reliable provider workflows, integrations, customer trust and accumulated operational data. AI alone is not a durable moat.

# 8. Competitive landscape

| Competitor | Current strengths | Strategic implication for Service Radar |
|---|---|---|
| Booksy | Established beauty / wellness booking platform and marketplace; booking, reminders, deposits and cancellation protection; large provider footprint claimed by Booksy | Do not compete on a generic salon calendar. Differentiate on route-aware mobile work and cross-channel revenue recovery. |
| Fresha | Marketplace discovery, provider profiles, online booking, payments, loyalty, marketing, reporting and smart pricing; charges a marketplace fee for new clients under its published pricing model | The marketplace + provider SaaS combination is already proven. Service Radar needs a sharper workflow advantage and local-market depth. |
| Goldie (formerly HeyGoldie) | Appointment scheduling, deposits / payments, recurring bookings, AI receptionist, waitlist, no-show protection and dynamic pricing | AI receptionist alone is not unique. Focus on the route optimiser and automated recovery across providers / customer acquisition. |
| BUK (Portugal) | Online appointment booking for salons, spas, personal trainers, physiotherapists and other appointment businesses; team schedules and reminders | Compete on a marketplace + managed payments + optimisation layer, not just a booking link. |
| Google Business Profile / Reserve with Google | Helps customers reach booking providers from Search / Maps; supports booking-provider integrations and booking links | Treat Google as an acquisition surface and integration opportunity, not simply as an application competitor. |

The old deck's competitor list remains useful as a historical snapshot, but the new deck should include Booksy, Fresha and Goldie at minimum. The old “HeyGoldie.com” should be updated to “Goldie”. Competitor features and pricing change, so a fresh hands-on mystery-shop before fundraising is recommended.

# 9. Business model and pricing proposal

## 9.1 Revenue streams

1. **Transaction commission:** a percentage of completed and paid service value processed through Service Radar.
2. **Provider subscription:** recurring monthly fee; higher plans lower the transaction commission.
3. **AI usage add-ons:** additional voice minutes / conversations above plan allowance, where relevant.
4. **Optional demand-generation services:** sponsored placement or campaigns, only after search ranking integrity and customer trust are established.
5. **Future integrations / enterprise:** multi-location reporting, advanced integrations and customised workflows.

Avoid making customer data sales or paid ranking the core business. Providers should be able to understand why they are shown in search results.

## 9.2 Illustrative plan architecture

These are test prices, not a final price list. Local price sensitivity, provider gross margins, average booking value and payment costs must be validated separately in Portugal, Poland and the UK.

| Plan | Indicative monthly price | Service Radar fee | Included scope |
|---|---:|---:|---|
| Pay-as-you-go | €0 / 0 PLN / £0 | 8% | Provider page, basic calendar, marketplace listing, standard booking and payment flow |
| Essentials | €24 / 99 PLN / £21 | 5% | Booking widget, deposits, reminders, basic customer history and funnel analytics |
| Growth | €69 / 279 PLN / £59 | 3.5% | Team tools, cancellation recovery, waitlist / promotions, customer rebooking journeys and advanced reporting |
| Frontdesk AI | €149 / 599 PLN / £129 | 2% | AI Frontdesk, web / WhatsApp / voice channel allowance, mobile route optimiser, flexible booking and advanced automation |

Commission should apply to the completed service value handled through the platform, with clear rules for refunds, tips, taxes and partial completion. Payment processing fees should be shown separately in the provider economics and should not be confused with Service Radar's take rate.

Test a second pricing variant where marketplace-acquired first-time customers attract a higher acquisition fee, while customers booked through the provider's own widget attract a lower software / transaction fee. This may feel fairer to established providers and aligns the platform's fee with the source of demand. Do not launch with too many fee rules; test them with a small provider panel.

## 9.3 AI trial and upgrade mechanism

Do not give the premium plan away indefinitely. Offer a short, measurable proof period:

- 30-day trial, or a fixed number of completed AI conversations and route-optimisation proposals, whichever is reached first.
- Show the provider how many enquiries were answered, how many bookings were completed, how many cancelled slots were recovered, how much booking value was recovered, and how much travel time / distance was saved.
- At the end of the trial, present the value delivered against the subscription price.
- Keep human takeover and manual scheduling available on lower plans.

The trial must be long enough to capture a real weekly rhythm. Route optimisation should not be judged for a provider who has too few mobile appointments to create useful route density.

## 9.4 Why providers may pay

The price should be justified by one or more measurable outcomes:

- One additional completed booking can cover a meaningful part of a monthly fee.
- Reduced no-shows protect provider time.
- A recovered cancellation produces revenue that might otherwise be lost.
- Less time answering calls and messages creates billable capacity.
- Fewer kilometres and less idle time allow more appointments or a shorter workday.

# 10. Payments, payouts and country strategy

## 10.1 First decide which payment model the product is

There are two different approaches:

**SaaS / connected merchant model:** the provider is the merchant for the service payment. The provider owns the payment relationship and ordinarily bears the first-line refund / dispute responsibilities. The platform earns a software fee or application fee.

**Marketplace payment model:** the platform owns the payment flow, collects from the customer, routes the provider's share and retains its commission. This is closer to the proposed “Airbnb-style” experience, but it also gives the platform greater responsibility for refunds, disputes, chargebacks, seller support and reconciliation. Mollie's documentation explicitly distinguishes the marketplace payment owner and its first-line chargeback liability from the SaaS platform model. [8]

The desired product sounds closer to a marketplace model. Do not collect customer funds into an ordinary Service Radar bank account and later transfer them manually. Use a regulated marketplace PSP and its approved balance / routing / payout architecture. Confirm the legal role, seller-of-record position, funds safeguarding, refund and chargeback allocation with the PSP and local counsel.

## 10.2 Provider payment schedule

A sensible target is:

- Customer pays a deposit or full amount at booking.
- Funds are processed and allocated through the marketplace PSP.
- Booking is marked completed after the appointment, using provider confirmation and a clear dispute window.
- Provider payout is initiated on the next scheduled payout run, targeting approximately 2-3 business days after service completion where the PSP and local payout rails permit.
- Refund, dispute and reserve rules are handled through the PSP's marketplace tools.

Treat 2-3 business days as a product target, not a promise until it is confirmed contractually for each country, payment method and payout schedule. Some local methods have different settlement timelines. Adyen documents managed / custom payouts and the ability to hold funds until payout; the commercial and regulatory configuration still needs approval. [2]

## 10.3 Payment provider evaluation

| Provider | Portugal | Poland | UK | Fit for Service Radar |
|---|---|---|---|---|
| **Adyen for Platforms** | Provider onboarding supported; MB WAY and Multibanco listed for platform payments | Provider onboarding supported; BLIK and Polish online banking listed | Provider onboarding supported; GBP payout support | **Best first enterprise candidate** for one marketplace stack across all three markets, with splits, balance management and payouts. Verify seller legal forms, onboarding and minimum commercial terms. [2][3] |
| **Stripe Connect** | Stripe is available for businesses in Portugal | Stripe is available for businesses in Poland | Stripe is available in the UK | Strong developer experience and Connect marketplace primitives. However, Stripe's current Przelewy24 onboarding requirements changed on 6 August 2026: platform users must be merchant of record and operate an identifiable online store, which may not fit a marketplace intermediary model. Validate Connect support for all required local methods and seller arrangements before selecting. [1][4] |
| **Mollie Connect** | Company availability in the EEA / UK; supports local Portuguese methods including MB WAY and Multibanco | Company availability in the EEA / UK; supports PLN and local methods should be checked per platform configuration | Company availability in the UK; GBP support | Strong candidate for delayed routing and platform / marketplace models. Important constraint: current marketplace onboarding docs say connected sub-merchants must be legal entities; private individuals cannot be onboarded. Confirm that target sole traders qualify in each country. [8][9] |
| **PayU Marketplace** | Not established as the one-provider choice for all three markets from the reviewed evidence | Purpose-built marketplace product with submerchant verification and automatic split to seller accounts | Not established as the one-provider choice for all three markets from the reviewed evidence | Strong Poland-specific fallback or local-market option. Verify country coverage, settlement timing and suitability for personal services. [5] |
| **ifthenpay** | Local payment methods and APIs include Multibanco, MB WAY and Payshop | Not a primary Poland solution | Not a primary UK solution | Useful Portugal local-method specialist. The public API documentation describes merchant keys and payment notifications, but does not establish marketplace split payouts; do not use as the core marketplace ledger without written confirmation. [6] |
| **GoCardless** | SEPA Direct Debit is relevant for recurring EUR payments | SEPA Direct Debit is relevant for recurring EUR payments | Bacs Direct Debit and UK Pay by Bank are relevant | Good for recurring provider subscriptions, instalments or recurring customer payments; not the main card / instant-payment checkout for individual bookings. Partner flows onboard merchants and pay them directly. [7] |

### Recommendation

Run an Adyen for Platforms commercial and technical discovery first because its published platform documentation covers all three target countries, marketplace payment splits, payout control, BLIK, MB WAY and Multibanco. [2][3] It also describes supported legal-entity types and notes that individuals need an associated sole proprietorship in the platform onboarding flow. [3]

In parallel, obtain a Stripe Connect proposal and a Mollie Connect eligibility response. Stripe may be easier to start with if the MVP is only in one country and uses cards, but the new Przelewy24 platform eligibility conditions make a blanket “Stripe covers all our markets” assumption unsafe. [4] Mollie is attractive for EUR / GBP / PLN routing, but the restriction on private individual sellers must be resolved before committing. [9]

A payment-provider proof-of-concept should test:

- A sole trader / self-employed provider in each of PT, PL and UK.
- Provider identity and business verification.
- Customer deposit and full-payment transactions.
- Split of platform commission and provider proceeds.
- Payout only after completion, with a 2-3 business-day target.
- Full and partial refund, late cancellation and no-show flows.
- Chargeback and negative-balance handling.
- Local payment methods: MB WAY / Multibanco, BLIK and UK cards / wallets / bank payments.
- Currency handling, fees, payout reports and reconciliation.

## 10.4 Country-specific payment approach

**Portugal**

- Cards and digital wallets.
- MB WAY and Multibanco should be treated as important local checkout candidates.
- ifthenpay is a useful local integration candidate, but its public API is merchant-key based and does not by itself establish a marketplace split / delayed payout architecture. [6]

**Poland**

- Cards, BLIK and Polish online banking should be evaluated.
- PayU Marketplace is a credible local marketplace candidate, while Adyen lists BLIK and Polish online banking for platform integrations. [2][5]
- Be careful with Przelewy24 through Stripe: new onboarding requirements from 6 August 2026 require the platform user to be merchant of record and to operate an identifiable online store. [4]

**United Kingdom**

- Cards, Apple Pay / Google Pay and bank payment options.
- Bacs Direct Debit can support recurring provider subscriptions or other recurring payments; it is not the default instrument for every one-off booking. [7]
- GBP payouts and seller onboarding must be validated within the selected platform PSP.

## 10.5 Crypto payments

**Recommendation: do not include native crypto payments in the first release.**

The initial customer value is convenience, trust and local payment acceptance. Adding crypto is unlikely to solve a primary booking problem for the target segments, while creating extra complexity around volatility, refunds, conversion, accounting, sanctions screening, customer support and payment-provider acceptance.

In the EU, MiCA requires authorisation for firms providing crypto-asset services, subject to the regulation's scope and exemptions. Operating a wallet, custody, exchange or crypto transfer service can therefore create a materially different regulatory burden from accepting ordinary card payments. [10]

In the UK, financial promotions rules apply to qualifying cryptoasset promotions to UK consumers, including where the firm is based overseas but the promotion can have an effect in the UK. [11]

A later, lower-risk route would be to integrate a licensed / authorised payment partner that accepts a supported cryptoasset and converts it to EUR, PLN or GBP before settlement. Service Radar should not hold customer crypto balances, issue a token or operate its own exchange in the MVP. Add it only if customer research demonstrates real demand and the PSP confirms the exact flow in all target countries.

# 11. Data protection, marketplace and regulatory workstreams

This is a product that connects customers and service providers, processes payments, uses location data and sends personalised offers. Compliance must be part of the product design rather than a late-stage legal task.

## 11.1 Seller verification and platform reporting

- Define a provider onboarding checklist per country: identity, legal / trading status, tax information, payout account, service category and any licence or insurance required for that category.
- Expect seller due diligence and annual reporting obligations. DAC7 covers personal services facilitated through digital platforms and requires platform operators in scope to collect / verify seller information and report seller and financial data. [14]
- The UK has its own reporting rules for digital platforms facilitating the provision of services, including personal services. [15]
- Build the data model and reporting exports early. Do not treat tax reporting as an optional future analytics feature.

## 11.2 Marketplace trust and safety

- Verify provider identity and business details.
- Define category-specific minimum standards, qualifications and insurance requirements.
- Provide a clear report / complaint route and moderation process.
- Use verified reviews from completed transactions.
- Keep an auditable record of refunds, complaints and provider suspensions.
- Where the EU Digital Services Act applies, online marketplaces have trader traceability and interface / consumer-information obligations. [16]

## 11.3 GDPR and customer data

- Document whether Service Radar is controller, joint controller or processor for each workflow. It may be a controller for its own marketplace, ranking, analytics and marketing; provider-specific processing can require a processor arrangement or another allocation depending on the actual service.
- Use data minimisation. Store only what is needed for booking, payment, service delivery, fraud prevention and agreed follow-up.
- Location and home address information needs strong access control. Do not expose exact customer addresses publicly; share them with the assigned provider only when needed.
- Avoid collecting health details in the first product version. Health data is a special category under GDPR and needs an Article 9 condition as well as an ordinary lawful basis. [13]
- Keep a clear retention policy for booking records, messages, call recordings and route history.
- Provide access, correction, deletion / restriction and portability workflows where applicable.
- Carry out a DPIA where the planned scale, profiling, location processing or sensitive data creates high risk.

## 11.4 Marketing and cancellation-recovery messages

The proposed slot-recovery feature must be designed around consent and channel rules.

- Separate essential booking messages from promotional messages.
- Obtain a clear opt-in for Service Radar marketplace offers and, where necessary, offers from named providers or provider categories.
- Record channel, purpose, wording, timestamp and the source of consent.
- Provide simple opt-out in every marketing message and maintain suppression lists.
- Do not assume that a customer who booked one salon has agreed to receive marketing from every other salon on the platform.
- In the UK, marketing email / text to individuals generally requires consent or a limited soft opt-in for the sender's own similar products / services; the ICO explains that this is not a general permission to market third-party services to new contacts. [17]
- Apply the relevant ePrivacy / electronic communications rules in Portugal and Poland as well as GDPR. Obtain local legal review before running cross-provider promotional campaigns.

## 11.5 Consumer rights, cancellations and refunds

- Clearly disclose who supplies the service, who takes payment, the full price, the amount charged now, the balance due, cancellation terms and refund treatment.
- Do not assume that every appointment for a specific date is exempt from the EU 14-day withdrawal right. EU guidance lists specific exceptions, but ordinary personal services should be reviewed against the exact national implementation and service type. [18]
- A cancellation fee or retained deposit should be proportionate, disclosed before booking and consistent with local consumer law.
- Build a rules engine for cancellation deadlines, provider-initiated cancellations, customer no-shows, partial refunds and exceptional circumstances.
- Provide an accessible dispute and refund route. Do not make customers negotiate directly with a provider for a payment refund if Service Radar owns the payment flow.

## 11.6 AI transparency and oversight

- Tell users clearly at the beginning of a direct interaction when they are speaking with an AI system. EU AI Act Article 50 transparency requirements apply from 2 August 2026. [12]
- Keep a human escalation route.
- Log agent actions and the source data used for booking decisions.
- Use deterministic validation for price, availability, payment and calendar changes.
- Keep route suggestions explainable: e.g. “This change is estimated to save 28 minutes of driving.”
- Avoid fully automated decisions that deny service or materially disadvantage customers without an appropriate legal basis and safeguards.

# 12. Technology and operating architecture

The product should be built around a reliable booking and payment core, with AI acting as an interface to approved workflows.

## 12.1 Core domains

- Identity, provider verification and permissions.
- Service catalogue, locations and service areas.
- Availability, booking and calendar state machine.
- Customer profiles and consent preferences.
- Payment intents, deposits, captures, refunds, platform fees and payouts.
- Messaging, templates and notification preferences.
- Cancellation recovery / waitlist campaigns.
- Route planning and travel-time matrices.
- Analytics and provider reporting.
- AI agent orchestration and action audit log.

## 12.2 Integration principles

- Use a payment abstraction so the business is not permanently coupled to one PSP.
- Use webhooks and idempotent event handling for payment state, booking confirmation and payout state.
- Never treat the browser redirect as proof of payment; confirm through signed PSP events / API state.
- Keep a ledger of gross customer payment, provider amount, platform commission, processing fee, refund, chargeback and payout.
- Use a dedicated routing / travel-time provider and cache carefully. Build the optimizer around time-dependent travel durations.
- Keep AI prompts separate from business rules. The agent may request an action; domain services validate and execute it.
- Store explicit consent and policy versions against the booking.

## 12.3 AI and optimiser architecture

The conversational agent should use structured tools such as `find_availability`, `create_booking`, `request_flexible_window`, `issue_payment_link`, `cancel_booking` and `offer_alternative_slot`. Each tool should enforce authorisation and validation server-side.

The route engine should evaluate possible routes and time windows using a constraint solver / vehicle-routing approach. The AI layer should communicate the results and negotiate customer preferences, not decide whether a route is feasible.

## 12.4 Privacy and security by design

- Encrypt sensitive data in transit and at rest.
- Minimise the number of staff and providers who can view exact home addresses.
- Use access scopes so a provider sees only their bookings and assigned customers.
- Do not store card data; use PSP-hosted or PSP-controlled payment components.
- Define deletion and retention policies for transcripts, calls, messages and location data.
- Conduct vendor due diligence for AI, messaging, telephony, maps and payment processors.

# 13. Go-to-market strategy

## 13.1 Launch philosophy: supply density before broad consumer marketing

A local marketplace with only a few providers and irregular availability will not retain consumer demand. Start by building a dense supply cluster, then drive consumer bookings into that cluster.

A practical pilot sequence:

1. Recruit 15-25 providers in one small geographic cluster, focused on one or two categories.
2. Get their service catalogue, availability, service area and payment requirements live.
3. Use the provider's existing audience to seed bookings through their own widget / link.
4. Use consumer marketplace search to generate incremental demand.
5. Run cancellation recovery and flexible-window experiments once there is enough booking density.
6. Collect baseline and post-launch performance data from every participating provider.

## 13.2 Suggested pilot geography

Use the Bieruń-Tychy-Mikołów corridor as a prototype for mobile route planning because it reflects the example in the product concept. Confirm the real pilot based on:

- number of mobile professionals willing to join;
- number of appointments per provider per day;
- geographic spread and average journey times;
- consumer demand by category;
- access to local provider communities;
- ability to support Polish-language onboarding and customer care.

## 13.3 Provider acquisition

- Founder-led sales to independent professionals and small businesses.
- Partnerships with beauty / wellness training schools and professional communities.
- Referral credits for providers who recruit another active provider.
- Demonstrations using the provider's real schedule and service area.
- Migration support for service catalogues and existing customer lists, respecting lawful basis and consent.
- A free or low-cost listing to reduce initial adoption friction.

## 13.4 Consumer acquisition

- Local SEO pages by service and city / neighbourhood.
- Search and map discovery.
- Provider booking widgets and QR codes that bring existing customers into the system.
- Expat, newcomer, accommodation and tourism partnerships for multilingual demand.
- Local community groups and social content.
- Last-minute offers for opted-in customers who want flexible appointments.

## 13.5 Influencer / creator rewards

Retain the original reward-system idea as an experiment, not a central product pillar.

- Pay rewards only on completed, paid bookings.
- Use unique referral links or codes and clear attribution windows.
- Cap rewards and block self-referrals / fake bookings.
- Require clear disclosure of paid or incentivised recommendations.
- Compare cost per first completed booking against paid search and provider referrals.

## 13.6 Country sequencing

Do not launch Portugal, Poland and the UK simultaneously unless there are already strong local operators and provider pipelines in each market.

Recommended sequence if no existing country-specific traction dictates otherwise:

1. **Poland pilot:** validate mobile route optimisation and provider workflows in one compact city cluster.
2. **Portugal expansion:** validate multilingual traveller / newcomer demand and local checkout with MB WAY / Multibanco.
3. **UK expansion:** launch once marketplace payments, reporting and support operations are proven; assess the local competitive and customer-acquisition economics.

A different sequence may be better if the founders already have a stronger provider pipeline in Portugal or the UK. The deciding factor should be access to supply and proof of demand, not founder nationality or market size alone.

# 14. Product roadmap and milestones

## Phase 0: validation and commercial discovery (0-6 weeks)

- Interview at least 20 providers across mobile and fixed-location services.
- Interview at least 30 consumers, including locals and newcomers / expats.
- Validate the pain of travel fragmentation, cancellation recovery and deposit abandonment separately.
- Obtain written PSP answers on legal seller types, payment ownership, splits, payout schedule and local methods.
- Choose the initial country, category and geography.
- Agree pilot success criteria and baseline data collection.

**Gate:** at least 10 providers willing to pilot, clear booking / payment workflows, and a feasible PSP route for the provider types.

## Phase 1: paid booking foundation (6-16 weeks)

- Provider onboarding and profile.
- Service catalogue, availability and calendar.
- Customer discovery and local search.
- Booking, confirmation, cancellation and rescheduling.
- One PSP integration and one launch country's local payment methods.
- Deposit / full prepayment settings.
- Provider payout and reconciliation dashboard.
- Basic event tracking and funnel analytics.

**Gate:** providers can complete real paid bookings without manual payment intervention; booking and payout reconciliation is accurate.

## Phase 2: revenue recovery (4-7 months)

- Automated waitlist.
- Cancellation slot detection.
- Discount rules and time-limited offers.
- Rebooking prompts and customer cadence settings.
- Deposit / checkout experiments.
- Recovery revenue and booking-conversion analytics.

**Gate:** demonstrate incremental filled capacity and acceptable customer opt-out / complaint rates.

## Phase 3: mobile scheduling intelligence (6-10 months)

- Provider radius and drive-time service areas.
- Flexible customer time windows.
- Traffic-aware travel estimates.
- Route optimisation suggestions.
- Multi-customer rescheduling proposals with confirmation chain.
- Provider pre-authorisation and human override.

**Gate:** demonstrate measurable time / distance reduction without increased late arrivals or customer complaints.

## Phase 4: AI Frontdesk and multi-country rollout (9-15 months)

- Web and WhatsApp AI Frontdesk.
- Inbound voice assistant after careful testing.
- Multi-language conversation and structured booking actions.
- Human escalation, audit log and transparent AI disclosure.
- Add second country after support, PSP, reporting and localisation playbooks work.

**Gate:** AI produces positive provider ROI after model, telephony, messaging and support costs.

# 15. Key performance indicators

## Marketplace health

- Active providers by category and service area.
- Search-to-provider-view rate.
- Provider-view-to-availability rate.
- Availability-to-booking conversion.
- New customer bookings and repeat bookings.
- Percentage of searches returning at least three genuinely bookable providers.

## Provider economics

- Completed bookings per active provider per week.
- Gross booking value (GBV / GMV) per provider.
- Average booking value.
- Revenue per available provider hour.
- Cancellation and no-show rate.
- Deposit loss / refund rate.
- Provider churn and subscription upgrade rate.

## Revenue Recovery

- Cancelled slots detected.
- Offers sent and delivered.
- Offer acceptance rate.
- Recovered slot rate.
- Incremental gross booking value recovered.
- Discount cost versus recovered contribution.
- Customer complaints and marketing opt-outs.

## Route optimisation

- Baseline and optimised drive time per provider day.
- Kilometres driven per completed appointment.
- Idle time between appointments.
- Number of schedule changes proposed / accepted.
- Minutes saved per day and incremental appointments made possible.
- Late arrival, cancellation and complaint rates after rescheduling.

## AI Frontdesk

- Enquiries answered without human intervention.
- Median response time.
- Enquiry-to-booking conversion.
- Booking completion accuracy.
- Human escalation rate.
- Provider minutes saved.
- Cost per completed AI-assisted booking.
- AI-attributed gross booking value and gross margin after usage costs.

## Financial and payment health

- Platform take rate and subscription ARPA.
- Net revenue retention.
- Provider acquisition cost and payback.
- Consumer acquisition cost and repeat purchase rate.
- PSP cost per transaction.
- Refund, dispute and chargeback rate.
- Payout success and reconciliation exceptions.

# 16. Illustrative financial model

The following scenarios are arithmetic examples to show how the model behaves. They are **not forecasts**, market estimates or a valuation model. They assume an average local-currency booking value converted to EUR for comparison and a blended monthly subscription across active providers.

| Scenario | Active providers | Completed bookings / provider / month | Average booking value | Monthly GMV | Blended commission | Subscription ARPA | Illustrative monthly platform revenue |
|---|---:|---:|---:|---:|---:|---:|---:|
| Pilot | 25 | 25 | €45 | €28,125 | 5.0% | €35 | €2,281 |
| Single-market traction | 100 | 35 | €50 | €175,000 | 4.5% | €45 | €12,375 |
| Multi-city scale | 500 | 45 | €55 | €1,237,500 | 4.0% | €55 | €77,000 |

Formula:

- Monthly GMV = active providers × completed bookings per provider × average booking value.
- Commission revenue = monthly GMV × blended commission.
- Subscription revenue = active providers × blended subscription ARPA.
- Platform revenue = commission revenue + subscription revenue.

The scenarios exclude payment processing fees, refunds, chargebacks, promotional discounts funded by Service Radar, AI / voice / messaging / mapping costs, customer support, sales, marketing, salaries, taxes and general overhead. They should be converted into a proper operating model once provider interviews reveal realistic booking frequency and average ticket size.

**Key unit economics to model next**

- Contribution per completed booking after PSP cost, platform fee, refund / dispute loss and any discount subsidy.
- Monthly contribution per provider after AI and messaging usage.
- Provider CAC payback period.
- Consumer CAC and repeat booking rate.
- AI cost per completed booking and per provider month.
- Route optimisation value: minutes / km saved translated into additional billable capacity.

Do not report total customer payment volume as Service Radar revenue. Distinguish GMV, provider payouts, platform commission, subscription revenue and PSP costs.

# 17. Principal risks and mitigations

| Risk | Why it matters | Mitigation |
|---|---|---|
| Marketplace cold start | Customers will not return if search results have little real availability | Launch one dense cluster; onboard supply first; use providers' own audiences |
| Payment-provider eligibility | Solo providers may not qualify under a chosen marketplace PSP model | Make sole trader onboarding a formal provider-selection gate; test in all three countries before architecture lock-in |
| Platform payment liability | Full prepayment and delayed payout increase refund, chargeback and support responsibility | Use an approved marketplace PSP; define seller / platform roles and reserve rules; maintain a transaction ledger |
| Deposit reduces conversion | Large upfront charges can cause checkout abandonment | Provider-level experiments; show deposit and policy early; compare completed revenue, not just conversion |
| Marketing consent | Cross-provider offers may be unlawful without the correct consent / channel basis | Granular opt-in, clear sender identity, separate service / marketing messages and suppression lists |
| Route changes create friction | Customer or provider may not accept rescheduling | Capture flexibility at booking; provider pre-authorisation; atomic confirmation chain; human override |
| Bad traffic estimates | A poor route can create late arrivals and damage trust | Time-dependent routing, travel buffers, confidence thresholds and provider feedback |
| AI makes a false promise | Incorrect availability, price or confirmation can create disputes | Structured tools, deterministic validation, audit logs and human escalation |
| Health data exposure | Healthcare categories may involve sensitive personal data | Start with lower-sensitivity categories; do not collect diagnosis / treatment details; DPIA before expansion |
| Competitors copy features | Booking, deposits and chatbots are readily copied | Build operational data, integrations, route density and workflow reliability |
| Provider disintermediation | Customer and provider may move off-platform after first booking | Deliver continuing value through calendar, payments, recovery, analytics and AI; avoid punitive lock-in |
| Multi-country complexity | Payment methods, taxes, reporting and consumer rules differ | One-country pilot; modular PSP layer; country launch checklist and local advice |
| Crypto complexity | Adds compliance and settlement risk without proven customer demand | Defer; only consider regulated provider with fiat settlement |

# 18. Strategic decisions to resolve

These are the highest-value founder decisions before turning this into an investor deck:

1. **First customer:** mobile independent professionals, fixed-location salons, or both in a controlled pilot?
2. **First geography:** Poland / Upper Silesia, Portugal, or a market where the team already has stronger provider access?
3. **Payment model:** SaaS connected merchant or platform-owned marketplace payment flow?
4. **Provider eligibility:** are the target providers registered sole traders, companies, or unregistered individuals?
5. **Provider payout promise:** what exact payout schedule can the PSP contract support after service completion?
6. **Customer deposit policy:** provider-configurable deposit versus a platform default? Who owns refund decisions?
7. **AI scope:** web / WhatsApp first, or phone-first? Which use cases are safe enough to automate?
8. **Route-change authority:** what can the system change automatically without a provider's per-change approval?
9. **Brand architecture:** Service Radar as umbrella and Frontdesk as premium module, or one brand only?
10. **Evidence:** what product exists today, what has been built, what has been tested, and what traction can be substantiated?

# 19. Proposed presentation structure

A 12-slide core deck is recommended. The presentation should tell one commercial story rather than list every feature.

| Slide | Title / topic | What it must prove | Suggested visual |
|---|---|---|---|
| 1 | Service Radar: the intelligent front desk for local services | Clear category and ambition | One-line proposition with customer + provider visual |
| 2 | The problem: booking is fragmented; provider time is wasted | Customer friction and provider economics | Two-sided problem diagram |
| 3 | The solution: discover, book, pay, recover, optimise | A complete workflow, not another directory | Customer-to-provider service journey |
| 4 | A better provider day | Show route and capacity optimisation | Bieruń-Tychy-Mikołów before / after route example |
| 5 | Empty slots become revenue | Prove cancellation recovery logic | C1 cancellation to C2 replacement timeline |
| 6 | Frontdesk AI answers and books | Explain premium product and channels | Web / WhatsApp / phone interaction flow |
| 7 | Why we can win | Distinguish from Booksy, Fresha, Goldie and BUK | Competitive matrix focused on workflow differentiation |
| 8 | Business model | Subscription + lower take rate at higher tiers | Plan ladder and transaction flow |
| 9 | Payments across three markets | Explain local methods and safe provider payouts | Country / PSP architecture map |
| 10 | Go-to-market | Show focused launch and supply density strategy | First city-cluster and provider acquisition flywheel |
| 11 | Roadmap, metrics and proof points | Show what exists and what must be validated | Milestones with measurable gates |
| 12 | Team and ask | Make the funding / partnership request specific | Team, contact details and one memorable number |

## 19.1 Optional appendix slides

- Payment-provider comparison and payout flow.
- Detailed pricing and unit-economics assumptions.
- Route optimisation example with constraints.
- Cancellation recovery workflow and consent controls.
- Regulatory / trust architecture.
- Market sizing methodology and market data once validated.

## 19.2 What the deck needs before it can be investor-ready

- Real product screenshots or a clickable prototype.
- Provider interviews and signed pilot commitments.
- Actual pilot geography and category.
- Number of active / onboarded providers.
- Bookings, GMV, repeat rate and conversion funnel if available.
- Evidence of cancellation recovery or route savings.
- Payment-provider confirmation and commercial quote.
- Customer acquisition channels and CAC assumptions.
- Funding ask, use of funds and runway, if fundraising is intended.

Do not fill the original “Actual status of the product” slide with generic roadmap language. It should contain verifiable product status and traction only.

# 20. Source notes and references

The original pitch outline is the source for the historical product framing and the named team. The research references below support the current provider, competitor and regulatory observations in this draft. Provider documentation and pricing can change; obtain written confirmation and commercial terms before committing.

1. Stripe, **Global availability**: https://stripe.com/global
2. Adyen, **Platforms**: https://docs.adyen.com/platforms
3. Adyen, **Onboarding steps for platforms / marketplaces**: https://docs.adyen.com/platforms/onboard-users/onboarding-steps and https://docs.adyen.com/marketplaces/verification-requirements/
4. Stripe, **Przelewy24 onboarding requirements** (including requirements effective 6 August 2026): https://support.stripe.com/questions/przelewy24-%28p24%29-onboarding-requirements
5. PayU Europe, **Marketplace**: https://developers.payu.com/europe/docs/services/marketplace/
6. ifthenpay, **API documentation**: https://www.ifthenpay.com/docs/en/
7. GoCardless, **Partner integrations**: https://docs.gocardless.com/docs/partner-integrations/how-partner-integrations-work
8. Mollie, **Connect overview**: https://docs.mollie.com/docs/connect-overview
9. Mollie, **Onboard merchants**: https://docs.mollie.com/docs/connect-onboard-merchants
10. EUR-Lex, **Regulation (EU) 2023/1114 (MiCA)**: https://eur-lex.europa.eu/eli/reg/2023/1114/oj/eng
11. UK Financial Conduct Authority, **Cryptoasset financial promotions**: https://www.fca.org.uk/firms/cryptoasset-financial-promotions-and-fiat-crypto-ramp-services
12. European Commission, **Transparency obligations under Article 50 of the AI Act**: https://digital-strategy.ec.europa.eu/en/faqs/transparency-obligations-under-article-50-ai-act
13. European Commission, **Data protection: special categories and automated decision-making**: https://commission.europa.eu/law/law-topic/data-protection/information-individuals_en
14. European Commission, **DAC7**: https://taxation-customs.ec.europa.eu/taxation/tax-transparency-cooperation/administrative-co-operation-and-mutual-assistance/dac7_en
15. UK HMRC, **Reporting rules for digital platforms**: https://www.gov.uk/government/publications/reporting-rules-for-digital-platforms/reporting-rules-for-digital-platforms
16. European Commission, **Digital Services Act marketplace obligations**: https://ec.europa.eu/commission/presscorner/api/files/document/print/en/ip_24_2326/IP_24_2326_EN.pdf
17. UK ICO, **Electronic mail marketing**: https://ico.org.uk/for-organisations/direct-marketing-and-privacy-and-electronic-communications/guide-to-pecr/electronic-and-telephone-marketing/electronic-mail-marketing/
18. Your Europe, **Consumer rights when shopping in the EU**: https://europa.eu/youreurope/citizens/consumers/shopping/shopping-consumer-rights/index_en.htm
19. Booksy, **Business platform**: https://biz.booksy.com/pl-pl
20. Fresha, **Marketplace and business features / pricing**: https://www.fresha.com/for-business/features/marketplace and https://www.fresha.com/pricing
21. Goldie, **Appointment scheduling and AI features**: https://heygoldie.com/features/appointment-scheduling
22. BUK, **FAQs / booking capabilities**: https://buk.pt/faqs
23. Google, **Set up bookings through a provider**: https://support.google.com/business/answer/7475773?hl=en

---
