# Naming

Some rules:
+ Controllers should be pluralised
+ view directory names should be the same as the controller name
+ Models should be singular

so for example

    /controllers/meeting_notes_controller.rb
    /views/meeting_notes/
    /models/meeting_note.rb

+ variables should be pluralised if they are a collection (array)
+ variables should be singular if they are a instance of a class/model

so for example

    @meeting_notes = MeetingNote.all
    @meeting_note = MeetingNote.find(1)
