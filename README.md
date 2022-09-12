# electron-detect-gpu

Print Gpu Info Like: 
```json
GPUFeatureStatus:
{
    "2d_canvas": "enabled",
    "canvas_oop_rasterization": "disabled_off",
    "direct_rendering_display_compositor": "disabled_off_ok",
    "gpu_compositing": "enabled",
    "multiple_raster_threads": "enabled_on",
    "opengl": "enabled_on",
    "rasterization": "enabled",
    "raw_draw": "disabled_off_ok",
    "video_decode": "enabled",
    "video_encode": "enabled",
    "vulkan": "disabled_off",
    "webgl": "enabled",
    "webgl2": "enabled",
    "webgpu": "disabled_off"
}

GPUInfo:
{
    "auxAttributes": {
        "amdSwitchable": false,
        "canSupportThreadedTextureMailbox": false,
        "dx12FeatureLevel": "Not supported",
        "glExtensions": "GL_AMD_performance_monitor GL_ANGLE_base_vertex_base_instance GL_ANGLE_base_vertex_base_instance_shader_builtin GL_ANGLE_client_arrays GL_ANGLE_depth_texture GL_ANGLE_framebuffer_blit GL_ANGLE_framebuffer_multisample GL_ANGLE_get_serialized_context_string GL_ANGLE_get_tex_level_parameter GL_ANGLE_instanced_arrays GL_ANGLE_lossy_etc_decode GL_ANGLE_memory_size GL_ANGLE_multi_draw GL_ANGLE_pack_reverse_row_order GL_ANGLE_program_cache_control GL_ANGLE_provoking_vertex GL_ANGLE_request_extension GL_ANGLE_robust_client_memory GL_ANGLE_texture_compression_dxt3 GL_ANGLE_texture_compression_dxt5 GL_ANGLE_texture_usage GL_ANGLE_translated_shader_source GL_CHROMIUM_bind_generates_resource GL_CHROMIUM_bind_uniform_location GL_CHROMIUM_color_buffer_float_rgb GL_CHROMIUM_color_buffer_float_rgba GL_CHROMIUM_copy_compressed_texture GL_CHROMIUM_copy_texture GL_CHROMIUM_lose_context GL_CHROMIUM_sync_query GL_EXT_EGL_image_external_wrap_modes GL_EXT_blend_func_extended GL_EXT_blend_minmax GL_EXT_clip_control GL_EXT_color_buffer_half_float GL_EXT_debug_label GL_EXT_debug_marker GL_EXT_discard_framebuffer GL_EXT_disjoint_timer_query GL_EXT_draw_buffers GL_EXT_draw_elements_base_vertex GL_EXT_float_blend GL_EXT_frag_depth GL_EXT_instanced_arrays GL_EXT_map_buffer_range GL_EXT_multi_draw_indirect GL_EXT_multisampled_render_to_texture GL_EXT_occlusion_query_boolean GL_EXT_read_format_bgra GL_EXT_robustness GL_EXT_sRGB GL_EXT_shader_texture_lod GL_EXT_texture_compression_bptc GL_EXT_texture_compression_dxt1 GL_EXT_texture_compression_rgtc GL_EXT_texture_compression_s3tc_srgb GL_EXT_texture_filter_anisotropic GL_EXT_texture_format_BGRA8888 GL_EXT_texture_norm16 GL_EXT_texture_rg GL_EXT_texture_storage GL_EXT_texture_type_2_10_10_10_REV GL_EXT_unpack_subimage GL_KHR_debug GL_KHR_parallel_shader_compile GL_NV_EGL_stream_consumer_external GL_NV_fence GL_NV_framebuffer_blit GL_NV_pack_subimage GL_NV_pixel_buffer_object GL_OES_EGL_image GL_OES_EGL_image_external GL_OES_compressed_EAC_R11_signed_texture GL_OES_compressed_EAC_R11_unsigned_texture GL_OES_compressed_EAC_RG11_signed_texture GL_OES_compressed_EAC_RG11_unsigned_texture GL_OES_compressed_ETC2_RGB8_texture GL_OES_compressed_ETC2_RGBA8_texture GL_OES_compressed_ETC2_punchthroughA_RGBA8_texture GL_OES_compressed_ETC2_punchthroughA_sRGB8_alpha_texture GL_OES_compressed_ETC2_sRGB8_alpha8_texture GL_OES_compressed_ETC2_sRGB8_texture GL_OES_depth24 GL_OES_depth32 GL_OES_draw_elements_base_vertex GL_OES_element_index_uint GL_OES_fbo_render_mipmap GL_OES_get_program_binary GL_OES_mapbuffer GL_OES_packed_depth_stencil GL_OES_rgb8_rgba8 GL_OES_standard_derivatives GL_OES_surfaceless_context GL_OES_texture_border_clamp GL_OES_texture_float GL_OES_texture_float_linear GL_OES_texture_half_float GL_OES_texture_half_float_linear GL_OES_texture_npot GL_OES_texture_stencil8 GL_OES_vertex_array_object GL_WEBGL_video_texture ",
        "glRenderer": "ANGLE (NVIDIA, NVIDIA GeForce RTX 3070 Direct3D11 vs_5_0 ps_5_0, D3D11-30.0.15.1215)",
        "glResetNotificationStrategy": 33362,
        "glVendor": "Google Inc. (NVIDIA)",
        "glVersion": "OpenGL ES 2.0.0 (ANGLE 2.1.18846 git hash: 4a65a669e11b)",
        "glWsExtensions": "EGL_EXT_create_context_robustness EGL_ANGLE_d3d_share_handle_client_buffer EGL_ANGLE_d3d_texture_client_buffer EGL_ANGLE_surface_d3d_texture_2d_share_handle EGL_ANGLE_query_surface_pointer EGL_ANGLE_window_fixed_size EGL_ANGLE_keyed_mutex EGL_ANGLE_surface_orientation EGL_ANGLE_direct_composition EGL_NV_post_sub_buffer EGL_KHR_create_context EGL_KHR_image EGL_KHR_image_base EGL_KHR_gl_texture_2D_image EGL_KHR_gl_texture_cubemap_image EGL_KHR_gl_renderbuffer_image EGL_KHR_get_all_proc_addresses EGL_KHR_stream EGL_KHR_stream_consumer_gltexture EGL_NV_stream_consumer_gltexture_yuv EGL_ANGLE_stream_producer_d3d_texture EGL_ANGLE_create_context_webgl_compatibility EGL_CHROMIUM_create_context_bind_generates_resource EGL_CHROMIUM_sync_control EGL_EXT_pixel_format_float EGL_KHR_surfaceless_context EGL_ANGLE_display_texture_share_group EGL_ANGLE_display_semaphore_share_group EGL_ANGLE_create_context_client_arrays EGL_ANGLE_program_cache_control EGL_ANGLE_robust_resource_initialization EGL_ANGLE_create_context_extensions_enabled EGL_ANDROID_blob_cache EGL_ANDROID_recordable EGL_ANGLE_image_d3d11_texture EGL_ANGLE_create_context_backwards_compatible EGL_KHR_no_config_context EGL_KHR_create_context_no_error EGL_KHR_reusable_sync ",
        "glWsVendor": "Google Inc. (NVIDIA)",
        "glWsVersion": "1.5 (ANGLE 2.1.18846 git hash: 4a65a669e11b)",
        "inProcessGpu": true,
        "initializationTime": 0,
        "isAsan": false,
        "jpegDecodeAcceleratorSupported": false,
        "maxMsaaSamples": "8",
        "optimus": false,
        "overlayInfo": {
            "directComposition": true,
            "nv12OverlaySupport": "DIRECT",
            "supportsOverlays": true,
            "yuy2OverlaySupport": "DIRECT"
        },
        "passthroughCmdDecoder": true,
        "pixelShaderVersion": "5.0",
        "sandboxed": false,
        "softwareRendering": false,
        "subpixelFontRendering": true,
        "supportsDx12": false,
        "supportsVulkan": false,
        "vertexShaderVersion": "5.0",
        "videoDecodeAcceleratorSupportedProfile": {
            "encrypted_only": false,
            "maxResolutionHeight": 8192,
            "maxResolutionWidth": 8192,
            "minResolutionHeight": 64,
            "minResolutionWidth": 64,
            "profile": 24
        },
        "visibilityCallbackCallCount": 0,
        "vulkanVersion": "Not supported"
    },
    "gpuDevice": [
        {
            "active": true,
            "cudaComputeCapabilityMajor": 0,
            "deviceId": 9348,
            "driverVendor": "NVIDIA",
            "driverVersion": "30.0.15.1215",
            "gpuPreference": 0,
            "revision": 161,
            "subSysId": -2017718205,
            "vendorId": 4318
        },
        {
            "active": false,
            "cudaComputeCapabilityMajor": 0,
            "deviceId": 140,
            "driverVersion": "10.0.19041.546",
            "gpuPreference": 0,
            "revision": 0,
            "subSysId": 0,
            "vendorId": 5140
        }
    ]
}
```