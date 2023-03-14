# Year-11-CS-Unit-7-Tutorial-Song

Lucas Wu

Your job is to create a class called Song.

A new Song will take two parameters: title and artist. Both of these properties will be declared as private.

Song mountMoose = new Song("Mount Moose", "The Snazzy Moose");

A new Song will allow outside-class access to these two properties via two public getter methods.

mountMoose.getTitle() => "Mount Moose";

mountMoose.getArtist() => "The Snazzy Moose";

You will also have to create an instance method named howMany().

The method takes an array of people who have listened to the song that day. The output should be how many new listeners the song gained on that day out of all listeners. Names should be treated in a case-insensitive manner, i.e. "John" is the same as "john".

Example
Song mountMoose = new Song("Mount Moose", "The Snazzy Moose");

// day 1 (or test 1)
mountMoose.howMany(new ArrayList<String>(Arrays.asList("John", "Fred", "BOb", "carl", "RyAn"))); => 5
// These are all new since they are the first listeners.

// day 2
mountMoose.howMany(new ArrayList<String>(Arrays.asList("JoHn", "Luke", "AmAndA"))); => 2
// Luke and Amanda are new, john already listened to it the previous day
Also if the same person listened to it more than once a day it should only count them once.

Example
Song mountMoose = new Song("Mount Moose", "The Snazzy Moose");

// day 1
mountMoose.howMany(new ArrayList<String>(Arrays.asList("John", "joHN", "carl"))); => 2

Good luck, have fun! :)
