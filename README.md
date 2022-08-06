# SwiftUIPhotosPickerExample

<div>
<img src="https://user-images.githubusercontent.com/6063541/183230946-de89f386-27b1-4cc4-9bce-7bf779bb0d2d.png" width="200">
　
<img src="https://user-images.githubusercontent.com/6063541/183230947-aa662bbd-7d65-47fe-992c-df068f6a0f87.png" width="200">
　
<img src="https://user-images.githubusercontent.com/6063541/183230949-7c27dd79-9991-4abe-9b3a-acace1692b01.png" width="200">


</div>

- on push Add Button

```
(
	0   CoreFoundation                      0x00007ff80041f225 __exceptionPreprocess + 242
	1   libobjc.A.dylib                     0x00007ff800049c6f objc_exception_throw + 48
	2   Foundation                          0x00007ff800f1b125 -[NSXPCDecoder _validateAllowedClass:forKey:allowingInvocations:] + 483
	3   Foundation                          0x00007ff800f1bb5b _decodeObject + 1153
	4   Foundation                          0x00007ff800f1c167 _decodeObjectAfterSettingAllowListForKey + 151
	5   Foundation                          0x00007ff800f1c1af -[NSXPCDecoder decodeObjectOfClasses:forKey:] + 38
	6   Foundation                          0x00007ff800e0ae20 -[NSItemProvider initWithCoder:] + 426
	7   Foundation                          0x00007ff800f1bba1 _decodeObject + 1223
	8   Foundation                          0x00007ff800f1ccd5 __44-[NSXPCDecoder _decodeArrayOfObjectsForKey:]_block_invoke + 40
	9   Foundation                          0x00007ff800f33f8c _NSXPCSerializationIterateArrayObject + 188
	10  Foundation                          0x00007ff800f1cc88 -[NSXPCDecoder _decodeArrayOfObjectsForKey:] + 205
	11  Foundation                          0x00007ff800cf5afd -[NSArray(NSArray) initWithCoder:] + 161
	12  Foundation                          0x00007ff800f1bba1 _decodeObject + 1223
	13  Foundation                          0x00007ff800f1b64f -[NSXPCDecoder _decodeObjectOfClasses:atObject:] + 128
	14  Foundation                          0x00007ff800d8840a _NSXPCSerializationDecodeInvocationObjectOnlyArgumentArray + 483
	15  Foundation                          0x00007ff800f1c7f9 -[NSXPCDecoder __decodeXPCObject:allowingSimpleMessageSend:outInvocation:outArguments:outArgumentsMaxCount:outMethodSignature:outSelector:isReply:replySelector:] + 1412
	16  Foundation                          0x00007ff800f1c202 -[NSXPCDecoder _decodeMessageFromXPCObject:allowingSimpleMessageSend:outInvocation:outArguments:outArgumentsMaxCount:outMethodSignature:outSelector:] + 55
	17  Foundation                          0x00007ff800f0cf54 -[NSXPCConnection _decodeAndInvokeMessageWithEvent:reply:flags:] + 435
	18  Foundation                          0x00007ff800f0f9dc message_handler_message + 79
	19  Foundation                          0x00007ff800f0eec0 message_handler + 140
	20  libxpc.dylib                        0x00007ff800080d00 _xpc_connection_call_event_handler + 56
	21  libxpc.dylib                        0x00007ff800081120 _xpc_connection_mach_event + 1015
	22  libdispatch.dylib                   0x000000010a36b085 _dispatch_client_callout4 + 9
	23  libdispatch.dylib                   0x000000010a38a1dc _dispatch_mach_msg_invoke + 806
	24  libdispatch.dylib                   0x000000010a372b19 _dispatch_lane_serial_drain + 368
	25  libdispatch.dylib                   0x000000010a38b46c _dispatch_mach_invoke + 555
	26  libdispatch.dylib                   0x000000010a372b19 _dispatch_lane_serial_drain + 368
	27  libdispatch.dylib                   0x000000010a373be2 _dispatch_lane_invoke + 496
	28  libdispatch.dylib                   0x000000010a381f63 _dispatch_workloop_worker_thread + 959
	29  libsystem_pthread.dylib             0x00007ff82fd27fd0 _pthread_wqthread + 326
	30  libsystem_pthread.dylib             0x00007ff82fd26f57 start_wqthread + 15
)
(
	0   CoreFoundation                      0x00007ff80041f225 __exceptionPreprocess + 242
	1   libobjc.A.dylib                     0x00007ff800049c6f objc_exception_throw + 48
	2   Foundation                          0x00007ff800d8865d _NSXPCSerializationDecodeInvocationObjectOnlyArgumentArray + 1078
	3   Foundation                          0x00007ff800f1c7f9 -[NSXPCDecoder __decodeXPCObject:allowingSimpleMessageSend:outInvocation:outArguments:outArgumentsMaxCount:outMethodSignature:outSelector:isReply:replySelector:] + 1412
	4   Foundation                          0x00007ff800f1c202 -[NSXPCDecoder _decodeMessageFromXPCObject:allowingSimpleMessageSend:outInvocation:outArguments:outArgumentsMaxCount:outMethodSignature:outSelector:] + 55
	5   Foundation                          0x00007ff800f0cf54 -[NSXPCConnection _decodeAndInvokeMessageWithEvent:reply:flags:] + 435
	6   Foundation                          0x00007ff800f0f9dc message_handler_message + 79
	7   Foundation                          0x00007ff800f0eec0 message_handler + 140
	8   libxpc.dylib                        0x00007ff800080d00 _xpc_connection_call_event_handler + 56
	9   libxpc.dylib                        0x00007ff800081120 _xpc_connection_mach_event + 1015
	10  libdispatch.dylib                   0x000000010a36b085 _dispatch_client_callout4 + 9
	11  libdispatch.dylib                   0x000000010a38a1dc _dispatch_mach_msg_invoke + 806
	12  libdispatch.dylib                   0x000000010a372b19 _dispatch_lane_serial_drain + 368
	13  libdispatch.dylib                   0x000000010a38b46c _dispatch_mach_invoke + 555
	14  libdispatch.dylib                   0x000000010a372b19 _dispatch_lane_serial_drain + 368
	15  libdispatch.dylib                   0x000000010a373be2 _dispatch_lane_invoke + 496
	16  libdispatch.dylib                   0x000000010a381f63 _dispatch_workloop_worker_thread + 959
	17  libsystem_pthread.dylib             0x00007ff82fd27fd0 _pthread_wqthread + 326
	18  libsystem_pthread.dylib             0x00007ff82fd26f57 start_wqthread + 15
)


```
