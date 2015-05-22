Frame Receiver
==============

The FrameReceiver software application grabs incoming frames from the Percival 
Mezzanine boards and hands them over via shared memory for further processing 
and storage on the same compute node.

.. doxygenindex::
   :project: framereceiver


API Reference Documentation
---------------------------


.. doxygenclass:: FrameReceiver::FrameReceiverApp
   :members:

.. doxygenclass:: FrameReceiver::IpcReactorTimer
   :members:

.. doxygenclass:: FrameReceiver::FrameDecoder
   :members:

.. doxygenclass:: FrameReceiver::FrameDecoderException
   :members:

   