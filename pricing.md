---

copyright:
  years: 2020, 2021
lastupdated: "2021-03-19"

keywords: pricing

subcollection: dl

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:DomainName: data-hd-keyref="DomainName"}
{:note: .note}
{:important: .important}
{:deprecated: .deprecated}
{:external: target="_blank" .external}
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:term: .term}  
{:generic: data-hd-programlang="generic"}
{:download: .download}  

# Pricing for {{site.data.keyword.dl_full_notm}}
{: #pricing-for-ibm-cloud-dl}

Pricing for {{site.data.keyword.dl_full}} (2.0) offerings is consistent for equivalent regions and bandwidth, as shown in the following monthly pricing table.
{:shortdesc}

{{site.data.keyword.dl_short}} pricing does NOT include any additional charges by service providers to enable connectivity to {{site.data.keyword.cloud_notm}}.  
{: important}

## Arranging for {{site.data.keyword.dl_short}} connectivity  
{: #arranging-for-dl-conectivity}

You, the customer, must arrange connectivity and billing with your service providers, independently of {{site.data.keyword.cloud_notm}}.

{{site.data.keyword.dl_short}} Dedicated creates a Letter Of Authorization / Connecting Facility Assignment (LOA/CFA) which is usable by any service provider who can reach the Meet Me Room that is specified on that LOA/CFA. The provider who is connecting to the LOA/CFA must include pricing for the cross-connect in their quote to you. {{site.data.keyword.cloud_notm}} does not order cross-connects on behalf of any customer.

{{site.data.keyword.dl_short}} Connect uses pre-established physical connections to support virtual connections that Do Not need a LOA/CFA, but do require ordering from the Service Provider. 

## Pricing for port charges
{: #pricing-for-dl-port-charges}

The following tables list the pricing for metered and unmetered port charges.

### Unmetered
{: #pricing-for-dl-port-charges-unmetered}

| Speed | US, Canada & EU | Asia Pacific | Brazil & Mexico |
|----|----|----|----|
|  50 Mbps |    $250 |    $333 |    $400 |
| 100 Mbps |    $500 |    $665 |    $800 |
| 200 Mbps |  $1,000 |  $1,330 |  $1,600 |
| 500 Mbps |  $2,500 |  $3,335 |  $4,000 |
|   1 Gbps |  $5,000 |  $6,650 |  $8,000 |
|   2 Gbps | $10,000 | $13,300 | $16,000 |
|   5 Gbps | $25,000 | $33,250 | $49,000 |
|  10 Gbps | $50,000 | $66,500 | $80,000 |
{: caption="Table 1. {{site.data.keyword.dl_short}} unmetered port charges" caption-side="top"}

### Metered  
{: #pricing-for-dl-port-charges-metered}

Provider speeds greater than 10 Gbps for Direct Link Connect incur metered billing only.
{: important}

| Speed | Global |
|----|----|
|  50 Mbps |   $40 |
| 100 Mbps |   $45 |
| 200 Mbps |   $60 |
| 500 Mbps |  $150 |
|   1 Gbps |  $250 |
|   2 Gbps |  $500 |
|   5 Gbps |$1,200 |
|  10 Gbps |$1,800 |
|  25 Gbps (IBM Connect only) |$2,999 |
|  40 Gbps (IBM Connect only) |$6,999 |
|  50 Gbps (IBM Connect only) |$7,999 |
| 100 Gbps (IBM Connect only)|$12,999 |
{: caption="Table 2. {{site.data.keyword.dl_short}} metered port charges" caption-side="top"}

Metered port fee pricing is determined by the bandwidth speed of the port.
{:note}


## Pricing for metered data transfer charges
{: #metered-data-transfer-charge}

The following table lists the pricing for metered data transfer charges.

| Tier | US, Canada & EU | Asia Pacific | Brazil & Mexico |
|----|----|----|----|
| Per GB | $0.025 | $0.050 | $0.140 |
{: caption="Table 3. {{site.data.keyword.dl_short}} metered data transfer charges" caption-side="top"}

Data transfer is for egress only, and varies based on region. Inbound data transfer to IBM Cloud is free.
{:note}

## Pricing for routing charges
{: #pricing-for-global-routing-charges}

The following sections list the pricing for local and global routing charges.

### Local routing charges
{: #pricing-local-routing-charges}

Local routing is the default routing option. It provides access to data centers within the same market as the {{site.data.keyword.dl_short}} PoP. There's no charge for Local routing.

### Global routing charges
{: #pricing-global-routing-charges}

Global routing expands access to include all {{site.data.keyword.cloud_notm}} data centers globally. There's no charge for Global routing on Direct Link 2.0.

Direct Link Classic will still carry the Global Routing charge.  

Details on the markets and other considerations can be found in our [FAQs](/docs/dl?topic=dl-faqs).
