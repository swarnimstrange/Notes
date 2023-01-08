# Android Multimedia Framework Architechture

- Multimedia is most important component on any mobile device in today's era.

- Multimedia on a mobile devices consits of MPEG standard, file format for the media and codecs for the same.

- Multimedia framework is used to process audio/video and output to get certain functionality including storage, playback and recording.

- Container format specify how to wrap various meta-data/stream, most is coded data by codec.

- A codec is a device or computer program capable of encoding and/or decoding a digital data stream or signal.

- File format is also called as container or wrapper format which specifies how different data elements and metadata coexist in a computer file or stream.

- Android multimedia architechture has two components of Open CORE and Open MAX and their usage.

# Open Core Multimedia Engine

- Android multimedia subsystem provided by Packet Video is a modular, extensible framework.

- provides following feature -:
    - Combining independent media processing components
    - File formats, codecs, streaming protocol components
    - rendering components

# OpenMax Multimedia Engine

- OpenMAX bridges Codec/Decode to multimedia framework. It is the integration layer (IL) interface with Open Core which is royality free and cross-platform API for comprehensive streaming media codec and application portability.