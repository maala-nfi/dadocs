.. _Tampering with the clock (iOS):

Tampering with the clock (iOS)
==============================

Timestamps are of significant importance when analyzing a smartphone. Whilst they can make or break 
an alibi, or can place a device on a location on a certain time, they can be misleading when the 
clock has been tampered with. We propose to start every investigation with an analysis of the clock 
settings, in order to be able to recognize if and when the clock corresponded with the correct time.

Recognizing if the time has been altered on a device isn't always evident. We look at different 
sources in order to establish a well-founded statement on the clock settings. One of such sources is
the database ``knowledgeC.db``.

knowledgeC
----------

The table ``ZOBJECT``...