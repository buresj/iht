# Internet History Token

## Rationale

Internet History Token (IHT) is an NFT that holds a URL of a public website in its metadata. IHT is thus an NFT that represents a record of a visit.

An owner of said “history token” holds a claim of visit and/or participation in an event mediated by a website. These claims can be validated, collected, rewarded, exchanged, used for authentication purposes, and more.

Unlike asset NFTs which usually hold a URL pointing to an image, video, or sound file, in the case of history tokens, it is an event that has been persisted on a blockchain. The URL specifies the place and the moment of minting signifies the time.

IHTs do not provide distinctiveness to a digital asset; they capture it. IHT is thus an inverted NFT—it does not provide what a digital asset lacks, but it digitalizes an aspect of the reality of using the internet, or at large, communicating, observing, experiencing, etc.

The promise of tokenization of digital space-time is a creation of “cross-website communities” and “ex-post commonality” based on rare or important events without the necessity to leave anonymity. IHT is a web 3.0 intermediary data-layer between the past and the future, providing new creative space for traditional web 1.0/2.0 sites and applications.

## Internet History Token Standard  (v1)

The following standard provides rules for a self-organizing ecosystem beyond specific technological implementations and attempts to ensure cross-compatibility and continuity.

The IHT standard is a consensus on how to communicate the internet’s past.

The IHT standard is a paradigm of NFT utility, not a specific technological innovation or a service per se. The subject of the standard is a form of persisted URL and methods for how its storage and later use should be communicated.

Definition:

**IHT is any NFT holding a URL string with appended query string, which consists of a selected IHT attribute name and a UNIX timestamp in milliseconds as its value.**

A public list of recognized IHT attribute names should be used to secure the continuity and recognizability of history tokens. Other names or aliases (like ‘his’ and ‘pre’) can be registered with the aim of increasing specificity and lowering conflict with the source's query parameters.

Example of links added to minted NFT, here ‘iht’, ‘his’ and ‘pre’ were added as signs of IHT.

```url
https://github.com/user/repository?iht=1643494560635
https://github.com/user/repository?his=1643494560635
https://github.com/user/repository?pre=1643494560635
```

[Here](https://polygonscan.com/tx/0x8144421f118205940c7835499de7e0659434860c96f177a4dd420af555c5186b) is a simple but a fully sufficient history token for *this* visit.

IHT works as a backlink, therefore websites/applications should have a way to handle incoming visits from token owners or their observers. For that purpose, a simple history file contains information for those producing applications that automate IHT creation.

```url
https://github.com/history.txt
```
The file communicates that any NFT minting service, e.g., browser extension, should use the `pre` parameter when storing the site’s URL. 

```txt
Parameter: pre
Descriptions: https://github.com/history.json
```
That way, websites can create specially curated content or provide claims of meaning for specific events on the site. 

```json
{
    "standard" : 1,
    "events": [
        "tokenUrl" : "",
        "from": "",
        "to" : "",
        "description": ""    
   ] 
}
```

The history file has two major functions:

1. To validate or provide descriptions for selected tokens from the site itself
2. To allow users, developers, and robots to search and collect descriptions of known events

## Validity and meaning

It is self-evident that the timestamp appended to the stored URL does not serve for validation or proof of the visit.

The time of minting of the IHT is information about the time of the visit. The appended URL timestamp declares the NFT as an IHT and communicates the event creation to the website owners, in case the URL is used as a backlink.

Two main actors are necessary for the IHT ecosystem: “minters” and “archivists.”

A minting service provides IHTs. An archivist service gives meaning and validity to IHTs (e.g. description of an event, video recording, print screen). A claim of participation becomes proof through an archive, as direct description links to known IHTs can be provided.

Both of these actors can be either independent services (e.g. browser extension & IHT wiki listing events) or hosted by the website/app itself.

## Principles

The above-described standards stem from two main principles: of “obscurity” and “reciprocity.”

### Principle of obscurity

IHT does not hold meaning by itself. A description of an event has to be provided externally, e.g. wiki pages, polling DAPP. A unique combination of an URL and time has to be explained elsewhere. Persisted URLs will lead nowhere as websites and their content change.

Adding a print-screen of a visit to the IHT metadata would produce unnecessary issues: possible private information in the screen, data storage increase, and overburdening IHT to hold meaning.

It's better when external validators/archivists emerge as a norm, not as resolvers of conflicts.

### Principle of reciprocity

If something happens on a website and it motivates the creation of IHTs by visitors, site owners should be able to recognize visits from stored URLs. At the same time, for automating archivists' works, the common sign of an IHT URL has to exist so that they can be found in a blockchain.

Because a stored URL in an IHT is meaningless by itself, website owners should be invited into the process of giving them meaning and thus creating content for moments observed as important or valuable.

## Effects

The goal of the above-mentioned principles is to establish and produce (self-)observational and communication systems; therefore, the IHT concept is not a singular service or product. We can speculate about the effect in two areas: economical (value, exchange) and cultural (identity, memories, and narratives).

### Value and exchange

“First!” or “I was here!” comments represent the value given to special occasions on websites. The IHT can fulfill the same function as these comments but makes the claims permanent and transferable outside the content of the website itself.

The value of the IHT can be made evident at the moment of their creation, e.g. when one watches a stream of a speedrunner that just broke a world record. However, if the occasion is not clear, they can be used for speculation – a visitor can believe this website/content creator will achieve fame; thus, anyone's position as an early adopter/fan/consumer can be unique, rare, or meaningful in various (future) contexts and proven by IHT.

The price of IHT creation is a factor that creates a strategizing limit on how many IHTs one wishes to produce. It is an incentive for services to provide limited collections for certain unique events if they happen. IHTs make a demand on blockchain but storing memories can provide validity and stability.

Valuable IHTs can be sold and transferred. It opens the capacity for success distribution—buying back early IHTs from my fans or strategizing about purchasing IHT-based promises. 

In summary:

1. Exchange of IHT for any other asset NFT
2. IHT payback or repayment ex-post
3. IHT evaluation of unique or improbable events
4. IHT strategizing and investment


### Memory and identity

NFT based memberships are a broadly discussed topic. In this case, it is membership-/commonality-based on a unique experience. Services can emerge, enabling users to display "what they have seen," which could be a way to create new communities and give shared meaning to subjective experiences.

URL-time-based identity, similarly to real-world space-time identities (e.g. generations or nationality), produces specific closeness and differentiation. Subcultures can emerge from experiences rather than around topics and preferences.

The collection of IHTs represents a biography. It is a set of collective and individual memories. Surfing the internet is a quest for IHTs, ones that can become famous or unique experiences, stories, and improbable connections. One can hold proof of discovery or innovation. 

IHT-based social networks would produce circles of varying types of IHT owners. Its upside-down social network, as one consumes the internet through them, emerges as the result of past experiences. 

A new type of audience emerges from those creating IHTs for the occasion and considering it worth remembering.


In summary:

1. IHT based commonality & identity
2. IHT based authentication & user exclusive content
3. IHT based meetings & connections
4. IHT based audiences
