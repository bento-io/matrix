# [Matrix](http://bento.io/matrix)
An interactive tool for quickly learning programming languages. Built by [Bento](http://bento.io/).

Curated by [@jonhmchan](http://twitter.com/jonhmchan). Like Bento or this project? [Leave me a tip](https://gratipay.com/JonHMChan).

## About
Matrix was built with the philosophy that programming languages are very similar, and with the question of seeing what those similarities might look like. It also meant to be a learning aid such that programmers that know one language can quickly learn another. This repository holds all the data that is used by Matrix, and is actively being edited.

## Contributing
Please read the notes below. Once changes are merged here, it will take some time for those changes to reflect on Bento because the repository needs to be pulled and the application refreshed.

## How this repository is structured
Every programming language that is here is separated into a folder. If you see that a programming language that you know is not in this repository, feel free to add it here. For each folder there are multiple topics, as outlined in the topics.json file at the root of this repository. If you are going to add new information on a topic, make sure that the filename is exactly as it is shown in the topics.json file, otherwise it will not appear.

Some things to note:
 * Only programming languages with similar features as those here will be merged in. These are languages that have many of the basic features one can expect: loops, variables, conditionals, etc. In some cases there are structures in a programming language that do not quite cleanly fall into any of the topics. For example, in Python, there are both lists and sets which may both be quite like arrays. You are free to put similar, but not exact topics together. Refrain from creating a new entry in the topics file unless it is a primary feature of *all* the languages that would appear here.
 * Be as concise and plain as possible. These are meant to be very quick references to get people programming in a language quickly. You can expect the users of this content to be intermediate programmers - people that are familiar with loops, conditionals, etc. That being said, it is not necessary to give context to every portion of a topic.
 * Stress practicality over formality. The content here is meant to get people productive in a language as quickly as possible. For example, in Go, there are arrays in the strict sense, but these are hardly ever used over slices in practice. The stance held for this project would be to have the content focus on slices and basic operations on that rather than its underlying data structure.
