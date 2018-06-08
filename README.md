# hello-world
Practice repository

pos_cam = pd.DataFrame(posibles_camiones)

f = open('camiones.txt', 'a+')
np.savetxt(f, pos_cam.values, fmt='%s')
f.close()
print('OK')
