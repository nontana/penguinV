##
# Directories containing makefiles
##
subsystem:
	-$(MAKE) -C bitmap_operation
	-$(MAKE) -C blob_detection
	-$(MAKE) -C function_pool
	-$(MAKE) -C image_function
	-$(MAKE) -C median_filter
	-$(MAKE) -C opencl/image_function
	-$(MAKE) -C thread_pool

.PHONY: clean
clean:
	-$(MAKE) clean -C bitmap_operation
	-$(MAKE) clean -C blob_detection
	-$(MAKE) clean -C function_pool
	-$(MAKE) clean -C image_function
	-$(MAKE) clean -C median_filter
	-$(MAKE) clean -C opencl/image_function
	-$(MAKE) clean -C thread_pool
