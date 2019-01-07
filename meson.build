project('raylib-meson-sample', 'c',
	version : '0.0.1',
	license: 'MIT'
)

raylib_proj = subproject('raylib')
raylib_dep = raylib_proj.get_variable('raylib_dep')

sources = [
	'raylib-meson-sample.c'
]

executable('raylib-meson-sample', sources,
	dependencies: [raylib_dep]
)
