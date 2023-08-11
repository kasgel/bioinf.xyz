---
title: "Analyse your own genome"
weight: 1
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---

# Analyse your own genome

The most obvious first bioinformatics project is of a personal nature: analysing your own genome. In this tutorial, I will show you how to obtain your own genomic code and analyse it for interesting features all yourself, using a hands-on approach. Going through this tutorial will require you to be able to work within Linux shell environments.

Getting all the way to the most interesting step, the actual analysis, requires going through a number of steps including [getting your DNA sequenced]({{< ref "_index.md#sequencing">}}), [preprocessing]({{< ref "preprocessing.md">}}) of the raw read files, [read mapping]({{< ref "read-mapping.md">}}), etc.

If you are interested in following this tutorial, you should get started with getting your DNA sequenced right away as this process can take many months.

I will be supplementing the tutorial with more materials as I perform them myself.

## Getting your DNA sequenced {#sequencing}

The first step is to get your own whole genome sequenced. But how or where? The first option is participating in a scientific study where your genome is used to make new scientific discoveries, and if you are lucky you can get the raw genomic data for free. The second option is paying a company to sequence your genome for you. The cost of this is somewhere between $200 to $2000, depending on how quickly you want your results and how deep you want the sequencing to be. With sequencing depth / coverage we refer to the average number that each nucleotide in your DNA is read. This is important because sequencing is not 100% accurate – there are sometimes errors and that's why you want each nucleotide read more than once. You should get your genome sequenced with a coverage of at least 30X.

The most popular companies performing Whole Genome Sequencing sequencing are:
- [Nebula Genomics (nebula.org)](https://nebula.org/whole-genome-sequencing-dna-test/). They sequence your DNA **in the US** and their 30X sequencing option can cost as little as 99 USD. However, sneaky Nebula also requires you to pay for a lifetime membership which costs 275 USD. Thus, the total cost of getting your DNA sequenced with Nebula is currently **374 USD**. Nebula promises results within 14 weeks from the day that they receive your sample.
- [Dante Labs](https://www.dantelabs.com/products/whole-genome-sequencing). They sequence samples **in the US and Italy**. If you are from Europe, your sample is not sent overseas but sequenced in Italy. Their cheapest sequencing package offers 30X coverage and costs currently **400 USD/EUR**. However, Dante Labs has frequent discounts and you may be able to catch a deal for as little as 200 USD. Although they promise results within 8 weeks, be warned you may have to wait much longer as they are currently [experiencing delays](https://www.reddit.com/r/DanteLabs/comments/15dl077/delays_at_dantelabs/).

Both above companies send you a saliva swab collection kit, which you have to send back to them using a prepaid shipping label. Collection and shipping it back is easy and convenient.

For the purposes of this tutorial, you should **not** go with companies like 23andme or My Ancestry, because they do not perform Whole Genome Sequencing. They sequence only a small subset (<0.1%) of your genome using microarray tests. This subset is enough for determining your haplogroup which can be used to deduce your ancestry. But these sequencing tests will not give you your whole genome and the data provided cannot be used to look at your genes or any interesting mutations within them.

You might also wonder if you could sequence your DNA yourself. You can read more about that below.

### Can I sequence my DNA myself?

If you have read into DNA sequencing at all, you might be aware that nanopore sequencing, one of the most recent Next Generation Sequencing technologies, has been marketed as [an extremely cheap sequencing alternative](https://www.forbes.com/sites/janetwburns/2018/01/29/handheld-device-gives-clearest-ever-view-of-human-genome-for-1000/?sh=5115512f36a5) where one device costs only approx. 1000 USD. To add more, the device is the size of an USB stick that you can conveniently plug into a computer and start sequencing. For those most privacy-aware this may sound tempting: could I sequence my DNA myself without trusting my DNA with a company?

To be honest, this thought crossed my mind when I was going to get my own DNA sequenced. After all, the cost of the device is not that much more compared to what you would pay to a company for the sequencing. "I could buy one, sequence my own DNA and then offer sequencing services for others", the entrepreneurial side of me thought.

The reality is, the device is not enough for you to perform sequencing. For one sequencing run you need to separately purchase reagents which will likely cost more than the device itself. You likely also need equipment for harvesting and culturing cells/tissue, because a simple cheek swab test would not provide enough DNA to perform nanopore sequencing on. Adding all the other costs, we are talking of tens of thousands of dollars in startup costs in addition to molecular biology knowledge to perform DNA sequencing using nanopore. Furthermore, nanopore sequencing is not as accurate as its alternative Illumina sequencing, which will make it more difficult 

Go with a company and let them sequence your DNA. Do not do this part yourself. If you are concerned about your privacy and want to minimise the (unlikely) chances of having to meet your biological clone in the future, read into the privacy policies of the sequencing companies before choosing the company.


## To be continued..