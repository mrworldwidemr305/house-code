# house-code
import pygame #bring in pygame library
pygame.init #initialize pygame

screen = pygame.display.set_mode((800, 800)) #create game screen
pygame.display.set_caption("A lovely House!") #window title

pygame.draw.rect(screen, (255, 228, 196), (500, 200, 300, 500))
pygame.draw.circle(screen, (200, 140, 0), (15, 49), 50)
pygame.draw.polygon(screen, (128, 128, 128), ((760, 100), (800, 200), (500, 200)))
pygame.draw.rect(screen, (69, 139, 0), (0, 650, 800, 150))
pygame.draw.circle(screen, (0, 0, 0), (50, 655), 20)
pygame.draw.circle(screen, (0, 0, 0), (150, 655), 20)

pygame.draw.rect(screen, (0, 0, 0), (600, 560, 50, 90),1)
pygame.draw.rect(screen, (0, 0, 0), (650, 560, 50, 90),1)

pygame.draw.rect(screen, (0, 0, 0), (580, 250, 30, 30),1)
pygame.draw.rect(screen, (0, 0 , 0), (550, 250, 30, 30),1)
pygame.draw.rect(screen, (0, 0, 0), (550, 280, 30, 30),1)
pygame.draw.rect(screen, (0, 0, 0), (580, 280, 30, 30),1)

pygame.draw.rect(screen, (0, 0, 0), (550, 400, 30, 30),1)
pygame.draw.rect(screen, (0, 0 , 0), (550, 430, 30, 30),1)
pygame.draw.rect(screen, (0, 0, 0), (580, 400, 30, 30),1)
pygame.draw.rect(screen, (0 ,0 , 0), (580, 430, 30, 30),1)

pygame.draw.rect(screen, (255, 48, 48), (0, 600, 90, 50))
pygame.draw.rect(screen, (220, 20, 60), (70, 560, 130, 90))

pygame.draw.rect(screen, (0, 0, 0), (700, 250, 30, 30),1)
pygame.draw.rect(screen, (0, 0, 0), (730, 250, 30, 30),1)
pygame.draw.rect(screen, (0,0 , 0), (700, 280, 30, 30),1)
pygame.draw.rect(screen, (0, 0, 0), (730, 280, 30, 30),1)

pygame.draw.rect(screen, (0, 0, 0), (700, 400, 30, 30),1)
pygame.draw.rect(screen, (0, 0 , 0), (730, 430, 30, 30),1)
pygame.draw.rect(screen, (0, 0 , 0), (730, 400, 30, 30),1)
pygame.draw.rect(screen, (0, 0, 0), (700, 430, 30, 30),1)
pygame.display.flip() #update graphics 
