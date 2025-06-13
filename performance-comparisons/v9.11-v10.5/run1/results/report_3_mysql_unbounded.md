### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | avg | 0s | 55ms | 55ms | 14932687.95
| CommandWebhookStore.Cleanup | avg | 2ms | 29ms | 27ms | 1166.94
| TokenStore.Cleanup | avg | 3ms | 30ms | 27ms | 981.00
| PostStore.GetPostReminderMetadata | avg | 16ms | 110ms | 94ms | 602.77
| EmojiStore.GetMultipleByName | avg | 33ms | 160ms | 127ms | 383.08
| UserStore.GetProfilesInChannel | avg | 29ms | 108ms | 79ms | 274.04
| BotStore.Get | avg | 19ms | 68ms | 49ms | 252.66
| ThreadStore.MarkAllAsReadByTeam | avg | 7ms | 22ms | 15ms | 201.05
| ChannelStore.GetSidebarCategory | avg | 23ms | 66ms | 43ms | 184.47
| TeamStore.GetMember | avg | 4ms | 10ms | 6ms | 157.41
| StatusStore.Get | avg | 13ms | 31ms | 18ms | 139.39
| PluginStore.List | avg | 16ms | 36ms | 20ms | 126.60
| PostStore.Delete | avg | 32ms | 71ms | 39ms | 120.90
| RoleStore.ChannelHigherScopedPermissions | avg | 28ms | 59ms | 31ms | 111.02
| StatusStore.GetByIds | avg | 23ms | 48ms | 25ms | 109.03
| UserStore.Get | avg | 12ms | 24ms | 12ms | 102.26
| ChannelStore.GetPinnedPostCount | avg | 19ms | 34ms | 15ms | 77.45
| FileInfoStore.GetForPost | avg | 22ms | 39ms | 17ms | 76.50
| JobStore.GetAllByStatus | avg | 22ms | 39ms | 17ms | 76.12
| UserStore.IsEmpty | avg | 8ms | 14ms | 6ms | 74.42
| ThreadStore.GetMembershipForUser | avg | 20ms | 35ms | 15ms | 73.41
| ThreadStore.GetTeamsUnreadForUser | avg | 20ms | 34ms | 14ms | 68.88
| ChannelStore.GetGuestCount | avg | 25ms | 42ms | 17ms | 66.95
| PostPersistentNotificationStore.GetSingle | avg | 22ms | 37ms | 15ms | 66.71
| UserStore.GetProfilesNotInChannel | avg | 23ms | 38ms | 15ms | 64.39
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 16ms | 26ms | 10ms | 62.99
| UserStore.GetProfileByIds | avg | 18ms | 29ms | 11ms | 61.39
| EmojiStore.GetByName | avg | 21ms | 34ms | 13ms | 61.14
| PreferenceStore.GetAll | avg | 20ms | 32ms | 12ms | 60.66
| ThreadStore.Get | avg | 22ms | 35ms | 13ms | 60.03
| UserStore.GetByUsername | avg | 22ms | 35ms | 13ms | 59.73
| PostPriorityStore.GetForPosts | avg | 29ms | 46ms | 17ms | 59.55
| PostAcknowledgementStore.GetForPosts | avg | 27ms | 43ms | 16ms | 59.47
| PostStore.GetSingle | avg | 19ms | 30ms | 11ms | 59.18
| ChannelStore.GetByName | avg | 19ms | 30ms | 11ms | 58.86
| DraftStore.Get | avg | 29ms | 46ms | 17ms | 58.73
| ThreadStore.GetThreadFollowers | avg | 22ms | 35ms | 13ms | 58.40
| GroupStore.GetByName | avg | 14ms | 22ms | 8ms | 57.94
| TeamStore.Get | avg | 18ms | 28ms | 10ms | 56.67
| ChannelStore.GetMembersForUserWithPagination | avg | 16ms | 25ms | 9ms | 56.14
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 14ms | 22ms | 8ms | 55.98
| PostStore.GetPostsByThread | avg | 21ms | 33ms | 12ms | 55.98
| LinkMetadataStore.Get | avg | 20ms | 31ms | 11ms | 55.93
| ChannelStore.GetMemberForPost | avg | 29ms | 45ms | 16ms | 55.68
| DraftStore.GetDraftsForUser | avg | 27ms | 42ms | 15ms | 55.57
| ThreadStore.GetThreadsForUser | avg | 27ms | 42ms | 15ms | 54.80
| ChannelStore.GetMembersForUser | avg | 24ms | 37ms | 13ms | 54.67
| ChannelStore.GetChannels | avg | 26ms | 40ms | 14ms | 53.99
| ThreadStore.GetThreadForUser | avg | 28ms | 43ms | 15ms | 53.97
| ThreadStore.GetTotalUnreadMentions | avg | 17ms | 26ms | 9ms | 53.96
| UserTermsOfServiceStore.GetByUser | avg | 17ms | 26ms | 9ms | 53.63
| TeamStore.GetChannelUnreadsForAllTeams | avg | 17ms | 26ms | 9ms | 53.56
| StatusStore.UpdateExpiredDNDStatuses | avg | 15ms | 23ms | 8ms | 53.52
| TeamStore.GetTeamsByUserId | avg | 17ms | 26ms | 9ms | 53.38
| GroupStore.GetGroups | avg | 23ms | 35ms | 12ms | 53.29
| ChannelStore.Get | avg | 45ms | 69ms | 24ms | 52.87
| ChannelStore.CreateDirectChannel | avg | 97ms | 148ms | 51ms | 52.75
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 17ms | 26ms | 9ms | 52.74
| FileInfoStore.GetByIds | avg | 27ms | 41ms | 14ms | 51.78
| WebhookStore.GetOutgoingByTeam | avg | 27ms | 41ms | 14ms | 51.53
| ChannelStore.SearchGroupChannels | avg | 29ms | 44ms | 15ms | 51.23
| UserStore.GetAllProfiles | avg | 14ms | 21ms | 7ms | 51.12
| TeamStore.GetTeamsForUser | avg | 16ms | 24ms | 8ms | 51.10
| ThreadStore.GetThreadUnreadReplyCount | avg | 24ms | 36ms | 12ms | 48.99
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 33ms | 49ms | 16ms | 48.91
| ProductNoticesStore.ClearOldNotices | avg | 4ms | 6ms | 2ms | 48.90
| UserAccessTokenStore.GetByToken | avg | 19ms | 28ms | 9ms | 48.63
| PostStore.Get | avg | 45ms | 67ms | 22ms | 48.63
| PostStore.GetPostReminders | avg | 12ms | 18ms | 6ms | 48.45
| ThreadStore.GetTotalUnreadThreads | avg | 17ms | 25ms | 8ms | 48.02
| ThreadStore.GetTotalThreads | avg | 17ms | 25ms | 8ms | 48.01
| TeamStore.GetAllPage | avg | 17ms | 25ms | 8ms | 47.70
| StatusStore.SaveOrUpdate | avg | 13ms | 19ms | 6ms | 47.62
| ChannelStore.GetMemberLastViewedAt | avg | 13ms | 19ms | 6ms | 46.84
| UserStore.GetUnreadCount | avg | 19ms | 28ms | 9ms | 46.67
| ChannelStore.GetChannelsByUser | avg | 15ms | 22ms | 7ms | 46.23
| PostPriorityStore.GetForPost | avg | 18ms | 26ms | 8ms | 44.87
| ChannelStore.SaveMember | avg | 83ms | 120ms | 37ms | 44.71
| UserStore.GetForLogin | avg | 16ms | 23ms | 7ms | 44.39
| PostStore.GetPostsBefore | avg | 25ms | 36ms | 11ms | 43.79
| PostStore.GetPostsAfter | avg | 21ms | 30ms | 9ms | 42.92
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 43ms | 61ms | 18ms | 41.89
| PostStore.GetEtag | avg | 27ms | 38ms | 11ms | 41.50
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 20ms | 28ms | 8ms | 40.20
| PreferenceStore.Get | avg | 23ms | 32ms | 9ms | 39.26
| JobStore.Save | avg | 8ms | 11ms | 3ms | 38.77
| PostAcknowledgementStore.GetForPost | avg | 18ms | 25ms | 7ms | 38.76
| PostStore.GetPostsSince | avg | 40ms | 55ms | 15ms | 37.92
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 40ms | 55ms | 15ms | 37.82
| ReactionStore.GetForPost | avg | 22ms | 30ms | 8ms | 37.02
| ChannelStore.GetTeamChannels | avg | 71ms | 97ms | 26ms | 36.62
| ChannelStore.AutocompleteInTeamForSearch | avg | 169ms | 230ms | 61ms | 36.02
| SessionStore.Get | avg | 26ms | 35ms | 9ms | 34.99
| ChannelStore.GetAllChannelMembersForUser | avg | 18ms | 24ms | 6ms | 33.85
| UserStore.GetProfilesByUsernames | avg | 22ms | 29ms | 7ms | 32.22
| SessionStore.GetLRUSessions | avg | 16ms | 21ms | 5ms | 32.04
| ChannelStore.GetFileCount | avg | 22ms | 29ms | 7ms | 32.00
| FileInfoStore.Get | avg | 20ms | 26ms | 6ms | 30.42
| SessionStore.Save | avg | 20ms | 26ms | 6ms | 30.41
| PostStore.SetPostReminder | avg | 17ms | 22ms | 5ms | 30.28
| PostStore.GetPosts | avg | 14ms | 18ms | 4ms | 28.55
| PreferenceStore.DeleteCategoryAndName | avg | 11ms | 14ms | 3ms | 28.24
| ChannelBookmarkStore.GetBookmarksForChannelSince | avg | 15ms | 19ms | 4ms | 27.07
| JobStore.UpdateStatusOptimistically | avg | 12ms | 15ms | 3ms | 25.37
| TeamStore.GetActiveMemberCount | avg | 213ms | 266ms | 53ms | 24.89
| UserStore.GetMany | avg | 29ms | 36ms | 7ms | 23.89
| ChannelStore.CreateInitialSidebarCategories | avg | 42ms | 52ms | 10ms | 23.86
| ChannelStore.GetChannelUnread | avg | 22ms | 27ms | 5ms | 22.77
| JobStore.GetNewestJobByStatusesAndType | avg | 27ms | 33ms | 6ms | 22.60
| UserStore.Search | avg | 93ms | 113ms | 20ms | 21.53
| FileInfoStore.SetContent | avg | 15ms | 18ms | 3ms | 20.32
| PreferenceStore.Save | avg | 19ms | 22ms | 3ms | 15.41
| ChannelStore.CreateSidebarCategory | avg | 53ms | 61ms | 8ms | 15.17
| TeamStore.SaveMember | avg | 100ms | 114ms | 14ms | 14.05
| UserStore.AutocompleteUsersInChannel | avg | 312ms | 345ms | 33ms | 10.58
| UserStore.Update | avg | 20ms | 22ms | 2ms | 9.79
| ProductNoticesStore.View | avg | 54ms | 59ms | 5ms | 9.33
| TeamStore.GetTotalMemberCount | avg | 195ms | 213ms | 18ms | 9.24
| PostStore.Save | avg | 27ms | 29ms | 2ms | 7.39
| UserStore.GetAllProfilesInChannel | avg | 627ms | 670ms | 43ms | 6.86
| UserStore.Save | avg | 86ms | 89ms | 3ms | 3.50
| ChannelStore.Save | avg | 65ms | 67ms | 2ms | 3.06
| ChannelStore.GetMemberCount | avg | 211ms | 215ms | 4ms | 1.90
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | p99 | 5ms | 694ms | 689ms | 13919.13
| CommandWebhookStore.Cleanup | p99 | 5ms | 241ms | 236ms | 4767.10
| TokenStore.Cleanup | p99 | 10ms | 241ms | 231ms | 2381.40
| UserStore.GetProfilesInChannel | p99 | 227ms | 4.125s | 3.898s | 1713.41
| PostStore.GetPostReminderMetadata | p99 | 140ms | 2.41s | 2.27s | 1615.69
| EmojiStore.GetMultipleByName | p99 | 232ms | 1.96s | 1.728s | 744.83
| BotStore.Get | p99 | 222ms | 1.795s | 1.573s | 707.76
| ChannelStore.CreateSidebarCategory | p99 | 99ms | 472ms | 373ms | 376.77
| JobStore.Save | p99 | 50ms | 231ms | 181ms | 362.00
| UserStore.GetProfilesNotInChannel | p99 | 97ms | 425ms | 328ms | 338.58
| ChannelStore.GetSidebarCategory | p99 | 214ms | 868ms | 654ms | 305.61
| TeamStore.GetMember | p99 | 49ms | 191ms | 142ms | 291.48
| RoleStore.ChannelHigherScopedPermissions | p99 | 191ms | 496ms | 305ms | 159.90
| ProductNoticesStore.ClearOldNotices | p99 | 10ms | 25ms | 15ms | 152.27
| SessionStore.GetSessionsExpired | p99 | 92ms | 222ms | 130ms | 140.55
| StatusStore.GetByIds | p99 | 246ms | 583ms | 337ms | 137.15
| ChannelStore.CreateDirectChannel | p99 | 858ms | 2.015s | 1.157s | 134.90
| JobStore.GetNewestJobByStatusesAndType | p99 | 250ms | 577ms | 327ms | 131.01
| PostStore.GetPostReminders | p99 | 82ms | 181ms | 99ms | 120.73
| ChannelStore.AutocompleteInTeamForSearch | p99 | 964ms | 2.106s | 1.142s | 118.46
| ChannelStore.GetTeamChannels | p99 | 438ms | 920ms | 482ms | 110.17
| StatusStore.Get | p99 | 216ms | 443ms | 227ms | 105.01
| PreferenceStore.DeleteCategoryAndName | p99 | 93ms | 190ms | 97ms | 104.02
| PostStore.Delete | p99 | 230ms | 467ms | 237ms | 103.15
| ThreadStore.MarkAllAsReadByTeam | p99 | 48ms | 98ms | 50ms | 103.09
| SessionStore.Remove | p99 | 80ms | 162ms | 82ms | 102.50
| JobStore.UpdateStatusOptimistically | p99 | 92ms | 186ms | 94ms | 102.45
| ThreadStore.GetTeamsUnreadForUser | p99 | 250ms | 483ms | 233ms | 93.20
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 210ms | 400ms | 190ms | 90.69
| EmojiStore.GetByName | p99 | 244ms | 465ms | 221ms | 90.40
| PostStore.GetPostsByThread | p99 | 242ms | 459ms | 217ms | 89.50
| ChannelStore.GetPinnedPostCount | p99 | 236ms | 447ms | 211ms | 89.37
| ThreadStore.GetMembershipForUser | p99 | 243ms | 458ms | 215ms | 88.37
| JobStore.GetAllByStatus | p99 | 246ms | 463ms | 217ms | 88.28
| TeamStore.GetActiveMemberCount | p99 | 493ms | 925ms | 432ms | 87.62
| GroupStore.GetGroups | p99 | 248ms | 461ms | 213ms | 85.86
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 245ms | 455ms | 210ms | 85.59
| ChannelStore.GetMembersForUser | p99 | 249ms | 458ms | 209ms | 84.07
| PostAcknowledgementStore.GetForPost | p99 | 220ms | 403ms | 183ms | 83.18
| ThreadStore.GetThreadFollowers | p99 | 252ms | 460ms | 208ms | 82.53
| PostAcknowledgementStore.GetForPosts | p99 | 400ms | 725ms | 325ms | 81.27
| PostPriorityStore.GetForPosts | p99 | 414ms | 750ms | 336ms | 81.24
| FileInfoStore.GetForPost | p99 | 268ms | 485ms | 217ms | 81.09
| ChannelStore.SaveMember | p99 | 890ms | 1.602s | 712ms | 79.99
| LinkMetadataStore.Get | p99 | 240ms | 431ms | 191ms | 79.49
| PostStore.GetSingle | p99 | 236ms | 423ms | 187ms | 79.22
| UserStore.GetByUsername | p99 | 233ms | 417ms | 184ms | 79.05
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 230ms | 410ms | 180ms | 78.43
| TeamStore.Get | p99 | 235ms | 419ms | 184ms | 78.28
| PostStore.Get | p99 | 469ms | 830ms | 361ms | 76.90
| UserStore.Get | p99 | 206ms | 363ms | 157ms | 76.24
| PostStore.GetPostsBefore | p99 | 250ms | 440ms | 190ms | 76.05
| PreferenceStore.GetAll | p99 | 246ms | 433ms | 187ms | 76.05
| PreferenceStore.Get | p99 | 249ms | 434ms | 185ms | 74.42
| TeamStore.GetTotalMemberCount | p99 | 490ms | 850ms | 360ms | 73.53
| ThreadStore.Get | p99 | 276ms | 478ms | 202ms | 73.23
| PostPersistentNotificationStore.GetSingle | p99 | 278ms | 481ms | 203ms | 72.91
| StatusStore.SaveOrUpdate | p99 | 182ms | 313ms | 131ms | 71.84
| PostStore.GetPostsAfter | p99 | 243ms | 417ms | 174ms | 71.71
| UserStore.GetProfileByIds | p99 | 237ms | 406ms | 169ms | 71.31
| UserStore.GetUnreadCount | p99 | 240ms | 410ms | 170ms | 70.80
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 240ms | 404ms | 164ms | 68.33
| ThreadStore.GetThreadUnreadReplyCount | p99 | 274ms | 458ms | 184ms | 67.27
| ChannelStore.GetByName | p99 | 235ms | 392ms | 157ms | 66.69
| ThreadStore.GetTotalUnreadMentions | p99 | 235ms | 391ms | 156ms | 66.52
| ChannelStore.Get | p99 | 425ms | 706ms | 281ms | 66.16
| UserTermsOfServiceStore.GetByUser | p99 | 236ms | 391ms | 155ms | 65.62
| SessionStore.Get | p99 | 259ms | 427ms | 168ms | 64.86
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 235ms | 387ms | 152ms | 64.77
| UserStore.IsEmpty | p99 | 139ms | 227ms | 88ms | 63.30
| WebhookStore.GetOutgoingByTeam | p99 | 290ms | 469ms | 179ms | 61.80
| ThreadStore.GetThreadForUser | p99 | 385ms | 621ms | 236ms | 61.30
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 235ms | 377ms | 142ms | 60.43
| FileInfoStore.GetByIds | p99 | 342ms | 546ms | 204ms | 59.72
| TeamStore.GetTeamsByUserId | p99 | 234ms | 371ms | 137ms | 58.51
| ThreadStore.GetTotalUnreadThreads | p99 | 234ms | 371ms | 137ms | 58.51
| UserStore.GetProfilesByUsernames | p99 | 243ms | 385ms | 142ms | 58.39
| ChannelStore.GetAllChannelMembersForUser | p99 | 199ms | 315ms | 116ms | 58.30
| DraftStore.GetDraftsForUser | p99 | 303ms | 478ms | 175ms | 57.69
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 540ms | 848ms | 308ms | 56.98
| ThreadStore.GetTotalThreads | p99 | 237ms | 369ms | 132ms | 55.77
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 223ms | 347ms | 124ms | 55.55
| ChannelStore.GetChannelUnread | p99 | 237ms | 368ms | 131ms | 55.24
| ChannelStore.GetMembersForUserWithPagination | p99 | 231ms | 358ms | 127ms | 54.92
| TeamStore.GetAllPage | p99 | 235ms | 362ms | 127ms | 54.00
| ChannelStore.GetChannels | p99 | 308ms | 473ms | 165ms | 53.59
| FileInfoStore.Get | p99 | 238ms | 364ms | 126ms | 52.85
| PostStore.GetEtag | p99 | 300ms | 458ms | 158ms | 52.69
| UserStore.GetForLogin | p99 | 230ms | 347ms | 117ms | 50.94
| TeamStore.GetTeamsForUser | p99 | 228ms | 344ms | 116ms | 50.77
| ChannelStore.GetFileCount | p99 | 230ms | 344ms | 114ms | 49.51
| UserStore.AutocompleteUsersInChannel | p99 | 970ms | 1.439s | 469ms | 48.37
| ReactionStore.GetForPost | p99 | 289ms | 428ms | 139ms | 48.14
| ThreadStore.GetThreadsForUser | p99 | 326ms | 479ms | 153ms | 46.90
| ChannelStore.GetGuestCount | p99 | 335ms | 488ms | 153ms | 45.67
| PostPriorityStore.GetForPost | p99 | 245ms | 356ms | 111ms | 45.24
| ChannelStore.GetMemberForPost | p99 | 338ms | 490ms | 152ms | 45.01
| DraftStore.Get | p99 | 341ms | 494ms | 153ms | 44.82
| UserStore.GetAllProfiles | p99 | 210ms | 302ms | 92ms | 43.74
| PostStore.GetPostsSince | p99 | 335ms | 478ms | 143ms | 42.72
| UserStore.UpdateLastLogin | p99 | 48ms | 68ms | 20ms | 41.54
| GroupStore.GetByName | p99 | 220ms | 307ms | 87ms | 39.51
| ChannelStore.GetChannelsByUser | p99 | 224ms | 311ms | 87ms | 38.86
| SessionStore.GetLRUSessions | p99 | 233ms | 320ms | 87ms | 37.33
| FileInfoStore.Save | p99 | 111ms | 151ms | 40ms | 36.08
| SessionStore.Save | p99 | 230ms | 304ms | 74ms | 32.22
| ChannelStore.SearchGroupChannels | p99 | 368ms | 480ms | 112ms | 30.44
| UserStore.Save | p99 | 253ms | 325ms | 72ms | 28.41
| UserStore.Search | p99 | 710ms | 889ms | 179ms | 25.20
| PluginStore.List | p99 | 213ms | 265ms | 52ms | 24.41
| PostStore.SearchPostsForUser | p99 | 601ms | 745ms | 144ms | 23.97
| ChannelStore.GetMemberLastViewedAt | p99 | 211ms | 257ms | 46ms | 21.76
| FileInfoStore.AttachToPost | p99 | 103ms | 124ms | 21ms | 20.43
| FileInfoStore.SetContent | p99 | 162ms | 195ms | 33ms | 20.35
| DraftStore.Upsert | p99 | 99ms | 118ms | 19ms | 19.15
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 60ms | 71ms | 11ms | 18.48
| PostStore.GetPosts | p99 | 208ms | 242ms | 34ms | 16.37
| ChannelStore.Save | p99 | 565ms | 657ms | 92ms | 16.28
| ChannelStore.GetPublicChannelsForTeam | p99 | 417ms | 482ms | 65ms | 15.57
| UserStore.UpdateUpdateAt | p99 | 66ms | 76ms | 10ms | 15.18
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 218ms | 250ms | 32ms | 14.66
| PostStore.SetPostReminder | p99 | 194ms | 221ms | 27ms | 13.88
| TeamStore.SaveMember | p99 | 436ms | 492ms | 56ms | 12.84
| ChannelStore.CreateInitialSidebarCategories | p99 | 418ms | 471ms | 53ms | 12.67
| PluginStore.Delete | p99 | 42ms | 47ms | 5ms | 11.96
| ThreadStore.MarkAsRead | p99 | 77ms | 86ms | 9ms | 11.68
| ChannelStore.GetMember | p99 | 90ms | 100ms | 10ms | 11.12
| PostStore.GetPostIdAfterTime | p99 | 64ms | 71ms | 7ms | 11.02
| SessionStore.UpdateLastActivityAt | p99 | 74ms | 82ms | 8ms | 10.85
| ProductNoticesStore.View | p99 | 414ms | 457ms | 43ms | 10.39
| SystemStore.GetByName | p99 | 69ms | 76ms | 7ms | 10.21
| StatusStore.UpdateExpiredDNDStatuses | p99 | 196ms | 215ms | 19ms | 9.69
| PluginStore.SetWithOptions | p99 | 89ms | 97ms | 8ms | 9.02
| UserStore.UpdateFailedPasswordAttempts | p99 | 78ms | 85ms | 7ms | 9.01
| PreferenceStore.Save | p99 | 213ms | 232ms | 19ms | 8.92
| AuditStore.Save | p99 | 79ms | 86ms | 7ms | 8.84
| ChannelStore.GetMemberCount | p99 | 891ms | 961ms | 70ms | 7.86
| StatusStore.UpdateLastActivityAt | p99 | 85ms | 91ms | 6ms | 7.10
| ThreadStore.UpdateMembership | p99 | 88ms | 94ms | 6ms | 6.85
| ChannelStore.IncrementMentionCount | p99 | 86ms | 91ms | 5ms | 5.80
| ThreadStore.MaintainMembership | p99 | 192ms | 203ms | 11ms | 5.72
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 76ms | 80ms | 4ms | 5.28
| PostStore.Update | p99 | 218ms | 229ms | 11ms | 5.04
| DraftStore.Delete | p99 | 92ms | 96ms | 4ms | 4.33
| ChannelStore.UpdateLastViewedAt | p99 | 166ms | 172ms | 6ms | 3.62
| PostStore.GetPostIdBeforeTime | p99 | 89ms | 92ms | 3ms | 3.36
| UserStore.GetAllProfilesInChannel | p99 | 2.392s | 2.433s | 41ms | 1.71
| PostStore.Save | p99 | 241ms | 245ms | 4ms | 1.66
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 34ms | 0s | -34ms | -100.12
| JobStore.Get | avg | 19ms | 0s | -19ms | -98.21
| PostPersistentNotificationStore.Get | avg | 7ms | 3ms | -4ms | -59.02
| DesktopTokensStore.DeleteOlderThan | avg | 5ms | 2ms | -3ms | -58.23
| ChannelStore.UpdateSidebarCategories | avg | 115ms | 58ms | -57ms | -49.60
| ChannelStore.GetMembers | avg | 74ms | 46ms | -28ms | -37.91
| PostPersistentNotificationStore.DeleteExpired | avg | 5ms | 3ms | -2ms | -37.43
| JobStore.UpdateOptimistically | avg | 11ms | 7ms | -4ms | -36.92
| JobStore.UpdateStatus | avg | 8ms | 5ms | -3ms | -36.92
| LinkMetadataStore.Save | avg | 6ms | 4ms | -2ms | -35.35
| UserStore.Count | avg | 191ms | 160ms | -31ms | -16.19
| SessionStore.GetSessionsExpired | avg | 16ms | 14ms | -2ms | -12.38
| PostStore.SearchPostsForUser | avg | 81ms | 78ms | -3ms | -3.70
| PostStore.AnalyticsPostCount | avg | 1.49s | 1.452s | -38ms | -2.55
| ChannelStore.Autocomplete | avg | 1.394s | 1.378s | -16ms | -1.15
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.Get | p99 | 176ms | 0s | -176ms | -100.16
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 293ms | 0s | -293ms | -100.00
| PostPersistentNotificationStore.Get | p99 | 71ms | 23ms | -48ms | -68.04
| ChannelStore.UpdateSidebarCategories | p99 | 1.42s | 480ms | -940ms | -66.20
| PostPersistentNotificationStore.DeleteExpired | p99 | 70ms | 31ms | -39ms | -55.33
| JobStore.UpdateStatus | p99 | 84ms | 42ms | -42ms | -50.28
| DesktopTokensStore.DeleteOlderThan | p99 | 10ms | 5ms | -5ms | -50.25
| ChannelStore.GetMembers | p99 | 480ms | 244ms | -236ms | -49.17
| UserStore.Update | p99 | 334ms | 231ms | -103ms | -30.82
| JobStore.UpdateOptimistically | p99 | 90ms | 69ms | -21ms | -23.31
| LinkMetadataStore.Save | p99 | 42ms | 34ms | -8ms | -19.16
| UserAccessTokenStore.GetByToken | p99 | 368ms | 330ms | -38ms | -10.34
| UserStore.GetMany | p99 | 444ms | 400ms | -44ms | -9.92
| JobStore.GetCountByStatusAndType | p99 | 499ms | 466ms | -33ms | -6.62
| ClusterDiscoveryStore.SetLastPingAt | p99 | 157ms | 149ms | -8ms | -5.08
| ThreadStore.MarkAllAsReadByChannels | p99 | 97ms | 94ms | -3ms | -3.09
| UserStore.Count | p99 | 494ms | 489ms | -5ms | -1.01
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| setPostReminder | avg | 103ms | 301ms | 198ms | 193.14
| updateReadStateAllThreadsByUser | avg | 8ms | 22ms | 14ms | 185.02
| deletePost | avg | 86ms | 185ms | 99ms | 114.89
| viewChannel | avg | 63ms | 116ms | 53ms | 84.19
| getUser | avg | 22ms | 38ms | 16ms | 73.14
| createChannel | avg | 721ms | 1.188s | 467ms | 64.75
| getPostsForChannel | avg | 200ms | 326ms | 126ms | 62.99
| getUsers | avg | 15ms | 24ms | 9ms | 60.97
| getDrafts | avg | 28ms | 45ms | 17ms | 59.73
| getPreferences | avg | 20ms | 32ms | 12ms | 59.05
| saveReaction | avg | 74ms | 117ms | 43ms | 58.47
| updateReadStateThreadByUser | avg | 194ms | 306ms | 112ms | 57.76
| getTeamsUnreadForUser | avg | 31ms | 49ms | 18ms | 57.65
| followThreadByUser | avg | 80ms | 125ms | 45ms | 56.32
| getThreadsForUser | avg | 27ms | 42ms | 15ms | 55.75
| getChannelMembersForUser | avg | 16ms | 25ms | 9ms | 55.41
| getChannelMembersForTeamForUser | avg | 24ms | 37ms | 13ms | 54.02
| deleteDraft | avg | 30ms | 46ms | 16ms | 53.90
| getChannelsForTeamForUser | avg | 26ms | 40ms | 14ms | 53.26
| getTeamsForUser | avg | 17ms | 26ms | 9ms | 52.69
| getPostThread | avg | 129ms | 196ms | 67ms | 52.06
| getAllTeams | avg | 19ms | 28ms | 9ms | 48.00
| searchGroupChannels | avg | 30ms | 44ms | 14ms | 47.40
| getTeamMembersForUser | avg | 17ms | 25ms | 8ms | 47.20
| getChannelsForUser | avg | 15ms | 22ms | 7ms | 45.64
| getCategoriesForTeamForUser | avg | 44ms | 63ms | 19ms | 42.89
| getPostsForChannelAroundLastUnread | avg | 76ms | 106ms | 30ms | 39.47
| upsertDraft | avg | 18ms | 25ms | 7ms | 38.92
| unfollowThreadByUser | avg | 65ms | 89ms | 24ms | 36.69
| getUsersByNames | avg | 22ms | 30ms | 8ms | 35.76
| autocompleteChannelsForTeamForSearch | avg | 170ms | 230ms | 60ms | 35.38
| updateCategoriesForTeamForUser | avg | 177ms | 230ms | 53ms | 29.89
| listChannelBookmarksForChannel | avg | 17ms | 22ms | 5ms | 29.22
| getChannelMember | avg | 29ms | 36ms | 7ms | 24.36
| createCategoryForTeamForUser | avg | 95ms | 115ms | 20ms | 21.04
| searchUsers | avg | 95ms | 114ms | 19ms | 20.06
| getTeamMember | avg | 10ms | 12ms | 2ms | 19.09
| getChannelUnread | avg | 25ms | 29ms | 4ms | 16.02
| getFileThumbnail | avg | 62ms | 71ms | 9ms | 14.59
| searchPostsInTeam | avg | 124ms | 140ms | 16ms | 12.90
| autocompleteUsers | avg | 273ms | 307ms | 34ms | 12.47
| getClientConfig | avg | 16ms | 18ms | 2ms | 12.29
| getTeamStats | avg | 243ms | 270ms | 27ms | 11.12
| addTeamMember | avg | 1.651s | 1.828s | 177ms | 10.72
| getFilePreview | avg | 69ms | 76ms | 7ms | 10.18
| addChannelMember | avg | 643ms | 702ms | 59ms | 9.17
| createDirectChannel | avg | 596ms | 635ms | 39ms | 6.54
| removeUserCustomStatus | avg | 322ms | 340ms | 18ms | 5.59
| getChannel | avg | 63ms | 65ms | 2ms | 3.17
| createUser | avg | 269ms | 275ms | 6ms | 2.23
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| setPostReminder | p99 | 815ms | 4.287s | 3.472s | 426.01
| createCategoryForTeamForUser | p99 | 246ms | 945ms | 699ms | 284.15
| createChannel | p99 | 2.446s | 9.2s | 6.754s | 276.08
| viewChannel | p99 | 558ms | 1.668s | 1.11s | 199.03
| deletePost | p99 | 865ms | 2.2s | 1.335s | 154.33
| autocompleteChannelsForTeamForSearch | p99 | 964ms | 2.106s | 1.142s | 118.46
| updateReadStateAllThreadsByUser | p99 | 48ms | 98ms | 50ms | 103.09
| followThreadByUser | p99 | 760ms | 1.525s | 765ms | 100.66
| getPostsForChannel | p99 | 2.467s | 4.828s | 2.361s | 95.70
| unfollowThreadByUser | p99 | 450ms | 870ms | 420ms | 93.29
| saveReaction | p99 | 830ms | 1.587s | 757ms | 91.15
| getTeamStats | p99 | 494ms | 925ms | 431ms | 87.19
| getPostsForChannelAroundLastUnread | p99 | 945ms | 1.766s | 821ms | 86.84
| logout | p99 | 486ms | 902ms | 416ms | 85.65
| getChannelMembersForTeamForUser | p99 | 249ms | 458ms | 209ms | 83.90
| getPreferences | p99 | 248ms | 439ms | 191ms | 77.01
| updateCategoriesForTeamForUser | p99 | 1.42s | 2.452s | 1.032s | 72.68
| autocompleteUsers | p99 | 972ms | 1.669s | 697ms | 71.69
| getTeamsUnreadForUser | p99 | 447ms | 767ms | 320ms | 71.59
| getUser | p99 | 282ms | 476ms | 194ms | 68.67
| createDirectChannel | p99 | 2.396s | 4.025s | 1.629s | 68.00
| getAllTeams | p99 | 244ms | 398ms | 154ms | 63.07
| getUsers | p99 | 226ms | 368ms | 142ms | 62.79
| upsertDraft | p99 | 234ms | 381ms | 147ms | 62.76
| getChannel | p99 | 497ms | 797ms | 300ms | 60.40
| getUsersByNames | p99 | 245ms | 392ms | 147ms | 59.96
| removeUserCustomStatus | p99 | 1.505s | 2.399s | 894ms | 59.40
| getTeamsForUser | p99 | 235ms | 373ms | 138ms | 58.83
| updateReadStateThreadByUser | p99 | 2.126s | 3.371s | 1.245s | 58.57
| getChannelUnread | p99 | 250ms | 395ms | 145ms | 58.03
| getTeamMembersForUser | p99 | 236ms | 371ms | 135ms | 57.30
| getChannelMembersForUser | p99 | 232ms | 359ms | 127ms | 54.80
| listChannelBookmarksForChannel | p99 | 239ms | 364ms | 125ms | 52.22
| getChannelsForTeamForUser | p99 | 313ms | 473ms | 160ms | 51.14
| getDrafts | p99 | 334ms | 496ms | 162ms | 48.56
| getCategoriesForTeamForUser | p99 | 577ms | 855ms | 278ms | 48.17
| getThreadsForUser | p99 | 337ms | 493ms | 156ms | 46.29
| getPostThread | p99 | 1.624s | 2.372s | 748ms | 46.07
| deleteDraft | p99 | 347ms | 494ms | 147ms | 42.34
| getUserStatusesByIds | p99 | 28ms | 39ms | 11ms | 39.81
| getChannelsForUser | p99 | 225ms | 311ms | 86ms | 38.30
| getUsersByIds | p99 | 64ms | 86ms | 22ms | 34.29
| searchPostsInTeam | p99 | 1.597s | 2.124s | 527ms | 33.00
| searchGroupChannels | p99 | 370ms | 480ms | 110ms | 29.72
| getChannelStats | p99 | 486ms | 627ms | 141ms | 28.98
| patchPost | p99 | 1.84s | 2.359s | 519ms | 28.21
| updatePreferences | p99 | 247ms | 316ms | 69ms | 27.88
| createUser | p99 | 1.563s | 1.947s | 384ms | 24.57
| searchUsers | p99 | 718ms | 891ms | 173ms | 24.09
| getChannelMember | p99 | 410ms | 505ms | 95ms | 23.15
| createGroupChannel | p99 | 4.761s | 5.75s | 989ms | 20.77
| getFileThumbnail | p99 | 418ms | 484ms | 66ms | 15.80
| getPublicChannelsForTeam | p99 | 417ms | 482ms | 65ms | 15.57
| getTeamMember | p99 | 157ms | 179ms | 22ms | 13.99
| addTeamMember | p99 | 8.457s | 9.594s | 1.137s | 13.44
| createPost | p99 | 4.613s | 5.209s | 596ms | 12.92
| getFilePreview | p99 | 430ms | 481ms | 51ms | 11.86
| getClientConfig | p99 | 222ms | 232ms | 10ms | 4.51
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | avg | 561ms | 212ms | -349ms | -62.16
| login | avg | 236ms | 146ms | -90ms | -38.16
| getChannelMembers | avg | 75ms | 47ms | -28ms | -37.42
| logout | avg | 155ms | 132ms | -23ms | -14.79
| getProfileImage | avg | 80ms | 69ms | -11ms | -13.79
| createPost | avg | 971ms | 865ms | -106ms | -10.91
| uploadFileStream | avg | 544ms | 525ms | -19ms | -3.49
| searchAllChannels | avg | 1.396s | 1.38s | -16ms | -1.15
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 480ms | 244ms | -236ms | -49.17
| login | p99 | 2.161s | 1.234s | -927ms | -42.90
| getProfileImage | p99 | 468ms | 452ms | -16ms | -3.42
| uploadFileStream | p99 | 2.163s | 2.09s | -73ms | -3.37
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 79ms| 86ms | 7ms | 8.840
| BotStore.Get |  Avg| 19ms| 68ms | 49ms | 252.663
| |  P99| 222ms| 1.795s | 1.573s | 707.762
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 15ms| 19ms | 4ms | 27.071
| |  P99| 218ms| 250ms | 32ms | 14.658
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 60ms| 71ms | 11ms | 18.484
| ChannelStore.Autocomplete |  Avg| 1.394s| 1.378s | -16ms | -1.148
| |  P99| 4.846s| 4.826s | -20ms | -0.413
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 169ms| 230ms | 61ms | 36.019
| |  P99| 964ms| 2.106s | 1.142s | 118.463
| ChannelStore.CreateDirectChannel |  Avg| 97ms| 148ms | 51ms | 52.755
| |  P99| 858ms| 2.015s | 1.157s | 134.897
| ChannelStore.CreateInitialSidebarCategories |  Avg| 42ms| 52ms | 10ms | 23.860
| |  P99| 418ms| 471ms | 53ms | 12.672
| ChannelStore.CreateSidebarCategory |  Avg| 53ms| 61ms | 8ms | 15.174
| |  P99| 99ms| 472ms | 373ms | 376.767
| ChannelStore.Get |  Avg| 45ms| 69ms | 24ms | 52.871
| |  P99| 425ms| 706ms | 281ms | 66.164
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 34ms| 0s | -34ms | -100.120
| |  P99| 293ms| 0s | -293ms | -100.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 18ms| 24ms | 6ms | 33.849
| |  P99| 199ms| 315ms | 116ms | 58.303
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 33ms| 49ms | 16ms | 48.905
| |  P99| 245ms| 455ms | 210ms | 85.585
| ChannelStore.GetByName |  Avg| 19ms| 30ms | 11ms | 58.861
| |  P99| 235ms| 392ms | 157ms | 66.693
| ChannelStore.GetChannelUnread |  Avg| 22ms| 27ms | 5ms | 22.769
| |  P99| 237ms| 368ms | 131ms | 55.238
| ChannelStore.GetChannels |  Avg| 26ms| 40ms | 14ms | 53.987
| |  P99| 308ms| 473ms | 165ms | 53.591
| ChannelStore.GetChannelsByUser |  Avg| 15ms| 22ms | 7ms | 46.226
| |  P99| 224ms| 311ms | 87ms | 38.856
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 20ms| 28ms | 8ms | 40.197
| |  P99| 240ms| 404ms | 164ms | 68.329
| ChannelStore.GetFileCount |  Avg| 22ms| 29ms | 7ms | 32.001
| |  P99| 230ms| 344ms | 114ms | 49.513
| ChannelStore.GetGuestCount |  Avg| 25ms| 42ms | 17ms | 66.953
| |  P99| 335ms| 488ms | 153ms | 45.666
| ChannelStore.GetMember |  Avg| 7ms| 8ms | 1ms | 14.563
| |  P99| 90ms| 100ms | 10ms | 11.120
| ChannelStore.GetMemberCount |  Avg| 211ms| 215ms | 4ms | 1.898
| |  P99| 891ms| 961ms | 70ms | 7.858
| ChannelStore.GetMemberForPost |  Avg| 29ms| 45ms | 16ms | 55.679
| |  P99| 338ms| 490ms | 152ms | 45.011
| ChannelStore.GetMemberLastViewedAt |  Avg| 13ms| 19ms | 6ms | 46.840
| |  P99| 211ms| 257ms | 46ms | 21.763
| ChannelStore.GetMembers |  Avg| 74ms| 46ms | -28ms | -37.911
| |  P99| 480ms| 244ms | -236ms | -49.167
| ChannelStore.GetMembersForUser |  Avg| 24ms| 37ms | 13ms | 54.668
| |  P99| 249ms| 458ms | 209ms | 84.067
| ChannelStore.GetMembersForUserWithPagination |  Avg| 16ms| 25ms | 9ms | 56.142
| |  P99| 231ms| 358ms | 127ms | 54.922
| ChannelStore.GetPinnedPostCount |  Avg| 19ms| 34ms | 15ms | 77.448
| |  P99| 236ms| 447ms | 211ms | 89.371
| ChannelStore.GetPublicChannelsForTeam |  Avg| 51ms| 52ms | 1ms | 1.950
| |  P99| 417ms| 482ms | 65ms | 15.569
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 43ms| 61ms | 18ms | 41.885
| |  P99| 540ms| 848ms | 308ms | 56.984
| ChannelStore.GetSidebarCategory |  Avg| 23ms| 66ms | 43ms | 184.470
| |  P99| 214ms| 868ms | 654ms | 305.607
| ChannelStore.GetTeamChannels |  Avg| 71ms| 97ms | 26ms | 36.624
| |  P99| 438ms| 920ms | 482ms | 110.171
| ChannelStore.IncrementMentionCount |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 86ms| 91ms | 5ms | 5.804
| ChannelStore.Save |  Avg| 65ms| 67ms | 2ms | 3.056
| |  P99| 565ms| 657ms | 92ms | 16.283
| ChannelStore.SaveMember |  Avg| 83ms| 120ms | 37ms | 44.709
| |  P99| 890ms| 1.602s | 712ms | 79.994
| ChannelStore.SearchGroupChannels |  Avg| 29ms| 44ms | 15ms | 51.233
| |  P99| 368ms| 480ms | 112ms | 30.437
| ChannelStore.UpdateLastViewedAt |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 166ms| 172ms | 6ms | 3.620
| ChannelStore.UpdateSidebarCategories |  Avg| 115ms| 58ms | -57ms | -49.599
| |  P99| 1.42s| 480ms | -940ms | -66.197
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 76ms| 80ms | 4ms | 5.279
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 12ms| 13ms | 1ms | 8.503
| |  P99| 157ms| 149ms | -8ms | -5.079
| CommandWebhookStore.Cleanup |  Avg| 2ms| 29ms | 27ms | 1166.936
| |  P99| 5ms| 241ms | 236ms | 4767.104
| DesktopTokensStore.DeleteOlderThan |  Avg| 5ms| 2ms | -3ms | -58.232
| |  P99| 10ms| 5ms | -5ms | -50.251
| DraftStore.Delete |  Avg| 9ms| 10ms | 1ms | 10.763
| |  P99| 92ms| 96ms | 4ms | 4.327
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 40ms| 55ms | 15ms | 37.821
| |  P99| 210ms| 400ms | 190ms | 90.689
| DraftStore.Get |  Avg| 29ms| 46ms | 17ms | 58.733
| |  P99| 341ms| 494ms | 153ms | 44.823
| DraftStore.GetDraftsForUser |  Avg| 27ms| 42ms | 15ms | 55.568
| |  P99| 303ms| 478ms | 175ms | 57.693
| DraftStore.Upsert |  Avg| 10ms| 11ms | 1ms | 9.876
| |  P99| 99ms| 118ms | 19ms | 19.148
| EmojiStore.GetByName |  Avg| 21ms| 34ms | 13ms | 61.143
| |  P99| 244ms| 465ms | 221ms | 90.397
| EmojiStore.GetMultipleByName |  Avg| 33ms| 160ms | 127ms | 383.079
| |  P99| 232ms| 1.96s | 1.728s | 744.829
| FileInfoStore.AttachToPost |  Avg| 11ms| 12ms | 1ms | 8.701
| |  P99| 103ms| 124ms | 21ms | 20.432
| FileInfoStore.Get |  Avg| 20ms| 26ms | 6ms | 30.424
| |  P99| 238ms| 364ms | 126ms | 52.849
| FileInfoStore.GetByIds |  Avg| 27ms| 41ms | 14ms | 51.780
| |  P99| 342ms| 546ms | 204ms | 59.718
| FileInfoStore.GetForPost |  Avg| 22ms| 39ms | 17ms | 76.498
| |  P99| 268ms| 485ms | 217ms | 81.085
| FileInfoStore.Save |  Avg| 11ms| 12ms | 1ms | 8.701
| |  P99| 111ms| 151ms | 40ms | 36.083
| FileInfoStore.SetContent |  Avg| 15ms| 18ms | 3ms | 20.322
| |  P99| 162ms| 195ms | 33ms | 20.349
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 14ms| 22ms | 8ms | 55.981
| |  P99| 223ms| 347ms | 124ms | 55.552
| GroupStore.GetByName |  Avg| 14ms| 22ms | 8ms | 57.941
| |  P99| 220ms| 307ms | 87ms | 39.509
| GroupStore.GetGroups |  Avg| 23ms| 35ms | 12ms | 53.287
| |  P99| 248ms| 461ms | 213ms | 85.860
| JobStore.Get |  Avg| 19ms| 0s | -19ms | -98.211
| |  P99| 176ms| 0s | -176ms | -100.160
| JobStore.GetAllByStatus |  Avg| 22ms| 39ms | 17ms | 76.122
| |  P99| 246ms| 463ms | 217ms | 88.283
| JobStore.GetCountByStatusAndType |  Avg| 36ms| 37ms | 1ms | 2.814
| |  P99| 499ms| 466ms | -33ms | -6.617
| JobStore.GetNewestJobByStatusesAndType |  Avg| 27ms| 33ms | 6ms | 22.604
| |  P99| 250ms| 577ms | 327ms | 131.010
| JobStore.Save |  Avg| 8ms| 11ms | 3ms | 38.770
| |  P99| 50ms| 231ms | 181ms | 362.000
| JobStore.UpdateOptimistically |  Avg| 11ms| 7ms | -4ms | -36.921
| |  P99| 90ms| 69ms | -21ms | -23.307
| JobStore.UpdateStatus |  Avg| 8ms| 5ms | -3ms | -36.921
| |  P99| 84ms| 42ms | -42ms | -50.285
| JobStore.UpdateStatusOptimistically |  Avg| 12ms| 15ms | 3ms | 25.368
| |  P99| 92ms| 186ms | 94ms | 102.450
| LinkMetadataStore.Get |  Avg| 20ms| 31ms | 11ms | 55.934
| |  P99| 240ms| 431ms | 191ms | 79.489
| LinkMetadataStore.Save |  Avg| 6ms| 4ms | -2ms | -35.355
| |  P99| 42ms| 34ms | -8ms | -19.162
| PluginStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 42ms| 47ms | 5ms | 11.965
| PluginStore.List |  Avg| 16ms| 36ms | 20ms | 126.597
| |  P99| 213ms| 265ms | 52ms | 24.413
| PluginStore.SetWithOptions |  Avg| 9ms| 10ms | 1ms | 11.338
| |  P99| 89ms| 97ms | 8ms | 9.022
| PostAcknowledgementStore.GetForPost |  Avg| 18ms| 25ms | 7ms | 38.763
| |  P99| 220ms| 403ms | 183ms | 83.182
| PostAcknowledgementStore.GetForPosts |  Avg| 27ms| 43ms | 16ms | 59.468
| |  P99| 400ms| 725ms | 325ms | 81.274
| PostPersistentNotificationStore.DeleteExpired |  Avg| 5ms| 3ms | -2ms | -37.427
| |  P99| 70ms| 31ms | -39ms | -55.328
| PostPersistentNotificationStore.Get |  Avg| 7ms| 3ms | -4ms | -59.025
| |  P99| 71ms| 23ms | -48ms | -68.042
| PostPersistentNotificationStore.GetSingle |  Avg| 22ms| 37ms | 15ms | 66.711
| |  P99| 278ms| 481ms | 203ms | 72.909
| PostPriorityStore.GetForPost |  Avg| 18ms| 26ms | 8ms | 44.872
| |  P99| 245ms| 356ms | 111ms | 45.235
| PostPriorityStore.GetForPosts |  Avg| 29ms| 46ms | 17ms | 59.553
| |  P99| 414ms| 750ms | 336ms | 81.241
| PostStore.AnalyticsPostCount |  Avg| 1.49s| 1.452s | -38ms | -2.550
| |  P99| 2.485s| 2.478s | -7ms | -0.282
| PostStore.Delete |  Avg| 32ms| 71ms | 39ms | 120.898
| |  P99| 230ms| 467ms | 237ms | 103.154
| PostStore.Get |  Avg| 45ms| 67ms | 22ms | 48.632
| |  P99| 469ms| 830ms | 361ms | 76.904
| PostStore.GetEtag |  Avg| 27ms| 38ms | 11ms | 41.497
| |  P99| 300ms| 458ms | 158ms | 52.685
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 64ms| 71ms | 7ms | 11.022
| PostStore.GetPostIdBeforeTime |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 89ms| 92ms | 3ms | 3.360
| PostStore.GetPostReminderMetadata |  Avg| 16ms| 110ms | 94ms | 602.766
| |  P99| 140ms| 2.41s | 2.27s | 1615.689
| PostStore.GetPostReminders |  Avg| 12ms| 18ms | 6ms | 48.448
| |  P99| 82ms| 181ms | 99ms | 120.732
| PostStore.GetPosts |  Avg| 14ms| 18ms | 4ms | 28.554
| |  P99| 208ms| 242ms | 34ms | 16.372
| PostStore.GetPostsAfter |  Avg| 21ms| 30ms | 9ms | 42.918
| |  P99| 243ms| 417ms | 174ms | 71.712
| PostStore.GetPostsBefore |  Avg| 25ms| 36ms | 11ms | 43.787
| |  P99| 250ms| 440ms | 190ms | 76.052
| PostStore.GetPostsByThread |  Avg| 21ms| 33ms | 12ms | 55.975
| |  P99| 242ms| 459ms | 217ms | 89.497
| PostStore.GetPostsSince |  Avg| 40ms| 55ms | 15ms | 37.915
| |  P99| 335ms| 478ms | 143ms | 42.715
| PostStore.GetSingle |  Avg| 19ms| 30ms | 11ms | 59.178
| |  P99| 236ms| 423ms | 187ms | 79.219
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 27ms| 29ms | 2ms | 7.388
| |  P99| 241ms| 245ms | 4ms | 1.662
| PostStore.SearchPostsForUser |  Avg| 81ms| 78ms | -3ms | -3.695
| |  P99| 601ms| 745ms | 144ms | 23.966
| PostStore.SetPostReminder |  Avg| 17ms| 22ms | 5ms | 30.275
| |  P99| 194ms| 221ms | 27ms | 13.882
| PostStore.Update |  Avg| 27ms| 28ms | 1ms | 3.693
| |  P99| 218ms| 229ms | 11ms | 5.044
| PreferenceStore.DeleteCategoryAndName |  Avg| 11ms| 14ms | 3ms | 28.245
| |  P99| 93ms| 190ms | 97ms | 104.021
| PreferenceStore.Get |  Avg| 23ms| 32ms | 9ms | 39.263
| |  P99| 249ms| 434ms | 185ms | 74.422
| PreferenceStore.GetAll |  Avg| 20ms| 32ms | 12ms | 60.660
| |  P99| 246ms| 433ms | 187ms | 76.051
| PreferenceStore.Save |  Avg| 19ms| 22ms | 3ms | 15.411
| |  P99| 213ms| 232ms | 19ms | 8.918
| ProductNoticesStore.ClearOldNotices |  Avg| 4ms| 6ms | 2ms | 48.896
| |  P99| 10ms| 25ms | 15ms | 152.270
| ProductNoticesStore.View |  Avg| 54ms| 59ms | 5ms | 9.331
| |  P99| 414ms| 457ms | 43ms | 10.389
| ReactionStore.GetForPost |  Avg| 22ms| 30ms | 8ms | 37.016
| |  P99| 289ms| 428ms | 139ms | 48.139
| RoleStore.ChannelHigherScopedPermissions |  Avg| 28ms| 59ms | 31ms | 111.017
| |  P99| 191ms| 496ms | 305ms | 159.895
| RoleStore.GetByNames |  Avg| 0s| 55ms | 55ms | 14932687.945
| |  P99| 5ms| 694ms | 689ms | 13919.131
| SessionStore.Get |  Avg| 26ms| 35ms | 9ms | 34.993
| |  P99| 259ms| 427ms | 168ms | 64.860
| SessionStore.GetLRUSessions |  Avg| 16ms| 21ms | 5ms | 32.044
| |  P99| 233ms| 320ms | 87ms | 37.332
| SessionStore.GetSessionsExpired |  Avg| 16ms| 14ms | -2ms | -12.376
| |  P99| 92ms| 222ms | 130ms | 140.546
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 16ms| 26ms | 10ms | 62.986
| |  P99| 230ms| 410ms | 180ms | 78.428
| SessionStore.Remove |  Avg| 8ms| 9ms | 1ms | 12.415
| |  P99| 80ms| 162ms | 82ms | 102.500
| SessionStore.Save |  Avg| 20ms| 26ms | 6ms | 30.405
| |  P99| 230ms| 304ms | 74ms | 32.223
| SessionStore.UpdateLastActivityAt |  Avg| 7ms| 8ms | 1ms | 13.599
| |  P99| 74ms| 82ms | 8ms | 10.855
| StatusStore.Get |  Avg| 13ms| 31ms | 18ms | 139.392
| |  P99| 216ms| 443ms | 227ms | 105.010
| StatusStore.GetByIds |  Avg| 23ms| 48ms | 25ms | 109.034
| |  P99| 246ms| 583ms | 337ms | 137.147
| StatusStore.SaveOrUpdate |  Avg| 13ms| 19ms | 6ms | 47.623
| |  P99| 182ms| 313ms | 131ms | 71.835
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 15ms| 23ms | 8ms | 53.518
| |  P99| 196ms| 215ms | 19ms | 9.694
| StatusStore.UpdateLastActivityAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 85ms| 91ms | 6ms | 7.099
| SystemStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 69ms| 76ms | 7ms | 10.212
| TeamStore.Get |  Avg| 18ms| 28ms | 10ms | 56.673
| |  P99| 235ms| 419ms | 184ms | 78.276
| TeamStore.GetActiveMemberCount |  Avg| 213ms| 266ms | 53ms | 24.888
| |  P99| 493ms| 925ms | 432ms | 87.617
| TeamStore.GetAllPage |  Avg| 17ms| 25ms | 8ms | 47.698
| |  P99| 235ms| 362ms | 127ms | 54.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 17ms| 26ms | 9ms | 53.557
| |  P99| 235ms| 377ms | 142ms | 60.428
| TeamStore.GetMember |  Avg| 4ms| 10ms | 6ms | 157.406
| |  P99| 49ms| 191ms | 142ms | 291.481
| TeamStore.GetTeamsByUserId |  Avg| 17ms| 26ms | 9ms | 53.379
| |  P99| 234ms| 371ms | 137ms | 58.512
| TeamStore.GetTeamsForUser |  Avg| 16ms| 24ms | 8ms | 51.099
| |  P99| 228ms| 344ms | 116ms | 50.769
| TeamStore.GetTotalMemberCount |  Avg| 195ms| 213ms | 18ms | 9.243
| |  P99| 490ms| 850ms | 360ms | 73.532
| TeamStore.SaveMember |  Avg| 100ms| 114ms | 14ms | 14.046
| |  P99| 436ms| 492ms | 56ms | 12.839
| ThreadStore.Get |  Avg| 22ms| 35ms | 13ms | 60.031
| |  P99| 276ms| 478ms | 202ms | 73.234
| ThreadStore.GetMembershipForUser |  Avg| 20ms| 35ms | 15ms | 73.406
| |  P99| 243ms| 458ms | 215ms | 88.368
| ThreadStore.GetTeamsUnreadForUser |  Avg| 20ms| 34ms | 14ms | 68.879
| |  P99| 250ms| 483ms | 233ms | 93.196
| ThreadStore.GetThreadFollowers |  Avg| 22ms| 35ms | 13ms | 58.399
| |  P99| 252ms| 460ms | 208ms | 82.530
| ThreadStore.GetThreadForUser |  Avg| 28ms| 43ms | 15ms | 53.973
| |  P99| 385ms| 621ms | 236ms | 61.300
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 24ms| 36ms | 12ms | 48.988
| |  P99| 274ms| 458ms | 184ms | 67.265
| ThreadStore.GetThreadsForUser |  Avg| 27ms| 42ms | 15ms | 54.797
| |  P99| 326ms| 479ms | 153ms | 46.904
| ThreadStore.GetTotalThreads |  Avg| 17ms| 25ms | 8ms | 48.007
| |  P99| 237ms| 369ms | 132ms | 55.773
| ThreadStore.GetTotalUnreadMentions |  Avg| 17ms| 26ms | 9ms | 53.958
| |  P99| 235ms| 391ms | 156ms | 66.524
| ThreadStore.GetTotalUnreadThreads |  Avg| 17ms| 25ms | 8ms | 48.022
| |  P99| 234ms| 371ms | 137ms | 58.508
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 17ms| 26ms | 9ms | 52.738
| |  P99| 235ms| 387ms | 152ms | 64.774
| ThreadStore.MaintainMembership |  Avg| 15ms| 16ms | 1ms | 6.604
| |  P99| 192ms| 203ms | 11ms | 5.717
| ThreadStore.MarkAllAsReadByChannels |  Avg| 9ms| 8ms | -1ms | -11.302
| |  P99| 97ms| 94ms | -3ms | -3.092
| ThreadStore.MarkAllAsReadByTeam |  Avg| 7ms| 22ms | 15ms | 201.050
| |  P99| 48ms| 98ms | 50ms | 103.093
| ThreadStore.MarkAsRead |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 77ms| 86ms | 9ms | 11.679
| ThreadStore.UpdateMembership |  Avg| 8ms| 9ms | 1ms | 11.778
| |  P99| 88ms| 94ms | 6ms | 6.851
| TokenStore.Cleanup |  Avg| 3ms| 30ms | 27ms | 981.000
| |  P99| 10ms| 241ms | 231ms | 2381.401
| UserAccessTokenStore.GetByToken |  Avg| 19ms| 28ms | 9ms | 48.634
| |  P99| 368ms| 330ms | -38ms | -10.340
| UserStore.AutocompleteUsersInChannel |  Avg| 312ms| 345ms | 33ms | 10.575
| |  P99| 970ms| 1.439s | 469ms | 48.365
| UserStore.Count |  Avg| 191ms| 160ms | -31ms | -16.193
| |  P99| 494ms| 489ms | -5ms | -1.011
| UserStore.Get |  Avg| 12ms| 24ms | 12ms | 102.255
| |  P99| 206ms| 363ms | 157ms | 76.238
| UserStore.GetAllProfiles |  Avg| 14ms| 21ms | 7ms | 51.118
| |  P99| 210ms| 302ms | 92ms | 43.740
| UserStore.GetAllProfilesInChannel |  Avg| 627ms| 670ms | 43ms | 6.860
| |  P99| 2.392s| 2.433s | 41ms | 1.714
| UserStore.GetByUsername |  Avg| 22ms| 35ms | 13ms | 59.733
| |  P99| 233ms| 417ms | 184ms | 79.055
| UserStore.GetForLogin |  Avg| 16ms| 23ms | 7ms | 44.392
| |  P99| 230ms| 347ms | 117ms | 50.941
| UserStore.GetMany |  Avg| 29ms| 36ms | 7ms | 23.892
| |  P99| 444ms| 400ms | -44ms | -9.916
| UserStore.GetProfileByIds |  Avg| 18ms| 29ms | 11ms | 61.394
| |  P99| 237ms| 406ms | 169ms | 71.306
| UserStore.GetProfilesByUsernames |  Avg| 22ms| 29ms | 7ms | 32.215
| |  P99| 243ms| 385ms | 142ms | 58.386
| UserStore.GetProfilesInChannel |  Avg| 29ms| 108ms | 79ms | 274.040
| |  P99| 227ms| 4.125s | 3.898s | 1713.414
| UserStore.GetProfilesNotInChannel |  Avg| 23ms| 38ms | 15ms | 64.395
| |  P99| 97ms| 425ms | 328ms | 338.581
| UserStore.GetUnreadCount |  Avg| 19ms| 28ms | 9ms | 46.669
| |  P99| 240ms| 410ms | 170ms | 70.803
| UserStore.IsEmpty |  Avg| 8ms| 14ms | 6ms | 74.421
| |  P99| 139ms| 227ms | 88ms | 63.301
| UserStore.Save |  Avg| 86ms| 89ms | 3ms | 3.496
| |  P99| 253ms| 325ms | 72ms | 28.405
| UserStore.Search |  Avg| 93ms| 113ms | 20ms | 21.529
| |  P99| 710ms| 889ms | 179ms | 25.197
| UserStore.Update |  Avg| 20ms| 22ms | 2ms | 9.794
| |  P99| 334ms| 231ms | -103ms | -30.823
| UserStore.UpdateFailedPasswordAttempts |  Avg| 7ms| 8ms | 1ms | 14.832
| |  P99| 78ms| 85ms | 7ms | 9.007
| UserStore.UpdateLastLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 48ms| 68ms | 20ms | 41.541
| UserStore.UpdateUpdateAt |  Avg| 6ms| 7ms | 1ms | 16.214
| |  P99| 66ms| 76ms | 10ms | 15.178
| UserTermsOfServiceStore.GetByUser |  Avg| 17ms| 26ms | 9ms | 53.633
| |  P99| 236ms| 391ms | 155ms | 65.624
| WebhookStore.GetOutgoingByTeam |  Avg| 27ms| 41ms | 14ms | 51.531
| |  P99| 290ms| 469ms | 179ms | 61.802
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 643ms| 702ms | 59ms | 9.175
| | P99| 4.597s| 4.609s | 12ms | 0.261
| addTeamMember | Avg| 1.651s| 1.828s | 177ms | 10.718
| | P99| 8.457s| 9.594s | 1.137s | 13.445
| autocompleteChannelsForTeamForSearch | Avg| 170ms| 230ms | 60ms | 35.377
| | P99| 964ms| 2.106s | 1.142s | 118.463
| autocompleteUsers | Avg| 273ms| 307ms | 34ms | 12.468
| | P99| 972ms| 1.669s | 697ms | 71.695
| createCategoryForTeamForUser | Avg| 95ms| 115ms | 20ms | 21.039
| | P99| 246ms| 945ms | 699ms | 284.146
| createChannel | Avg| 721ms| 1.188s | 467ms | 64.749
| | P99| 2.446s| 9.2s | 6.754s | 276.076
| createDirectChannel | Avg| 596ms| 635ms | 39ms | 6.542
| | P99| 2.396s| 4.025s | 1.629s | 67.999
| createGroupChannel | Avg| 1.019s| 1.028s | 9ms | 0.883
| | P99| 4.761s| 5.75s | 989ms | 20.774
| createPost | Avg| 971ms| 865ms | -106ms | -10.913
| | P99| 4.613s| 5.209s | 596ms | 12.919
| createUser | Avg| 269ms| 275ms | 6ms | 2.232
| | P99| 1.563s| 1.947s | 384ms | 24.571
| deleteDraft | Avg| 30ms| 46ms | 16ms | 53.902
| | P99| 347ms| 494ms | 147ms | 42.343
| deletePost | Avg| 86ms| 185ms | 99ms | 114.893
| | P99| 865ms| 2.2s | 1.335s | 154.331
| followThreadByUser | Avg| 80ms| 125ms | 45ms | 56.320
| | P99| 760ms| 1.525s | 765ms | 100.660
| getAllTeams | Avg| 19ms| 28ms | 9ms | 48.004
| | P99| 244ms| 398ms | 154ms | 63.071
| getCategoriesForTeamForUser | Avg| 44ms| 63ms | 19ms | 42.885
| | P99| 577ms| 855ms | 278ms | 48.173
| getChannel | Avg| 63ms| 65ms | 2ms | 3.171
| | P99| 497ms| 797ms | 300ms | 60.399
| getChannelMember | Avg| 29ms| 36ms | 7ms | 24.362
| | P99| 410ms| 505ms | 95ms | 23.146
| getChannelMembers | Avg| 75ms| 47ms | -28ms | -37.421
| | P99| 480ms| 244ms | -236ms | -49.167
| getChannelMembersForTeamForUser | Avg| 24ms| 37ms | 13ms | 54.022
| | P99| 249ms| 458ms | 209ms | 83.899
| getChannelMembersForUser | Avg| 16ms| 25ms | 9ms | 55.408
| | P99| 232ms| 359ms | 127ms | 54.796
| getChannelStats | Avg| 27ms| 26ms | -1ms | -3.753
| | P99| 486ms| 627ms | 141ms | 28.984
| getChannelUnread | Avg| 25ms| 29ms | 4ms | 16.024
| | P99| 250ms| 395ms | 145ms | 58.029
| getChannelsForTeamForUser | Avg| 26ms| 40ms | 14ms | 53.264
| | P99| 313ms| 473ms | 160ms | 51.136
| getChannelsForUser | Avg| 15ms| 22ms | 7ms | 45.644
| | P99| 225ms| 311ms | 86ms | 38.298
| getClientConfig | Avg| 16ms| 18ms | 2ms | 12.286
| | P99| 222ms| 232ms | 10ms | 4.514
| getDrafts | Avg| 28ms| 45ms | 17ms | 59.735
| | P99| 334ms| 496ms | 162ms | 48.563
| getFilePreview | Avg| 69ms| 76ms | 7ms | 10.178
| | P99| 430ms| 481ms | 51ms | 11.856
| getFileThumbnail | Avg| 62ms| 71ms | 9ms | 14.593
| | P99| 418ms| 484ms | 66ms | 15.799
| getPostThread | Avg| 129ms| 196ms | 67ms | 52.058
| | P99| 1.624s| 2.372s | 748ms | 46.072
| getPostsForChannel | Avg| 200ms| 326ms | 126ms | 62.987
| | P99| 2.467s| 4.828s | 2.361s | 95.699
| getPostsForChannelAroundLastUnread | Avg| 76ms| 106ms | 30ms | 39.467
| | P99| 945ms| 1.766s | 821ms | 86.841
| getPreferences | Avg| 20ms| 32ms | 12ms | 59.047
| | P99| 248ms| 439ms | 191ms | 77.009
| getProfileImage | Avg| 80ms| 69ms | -11ms | -13.794
| | P99| 468ms| 452ms | -16ms | -3.419
| getPublicChannelsForTeam | Avg| 53ms| 54ms | 1ms | 1.899
| | P99| 417ms| 482ms | 65ms | 15.569
| getTeamMember | Avg| 10ms| 12ms | 2ms | 19.090
| | P99| 157ms| 179ms | 22ms | 13.986
| getTeamMembersForUser | Avg| 17ms| 25ms | 8ms | 47.201
| | P99| 236ms| 371ms | 135ms | 57.302
| getTeamStats | Avg| 243ms| 270ms | 27ms | 11.118
| | P99| 494ms| 925ms | 431ms | 87.191
| getTeamsForUser | Avg| 17ms| 26ms | 9ms | 52.694
| | P99| 235ms| 373ms | 138ms | 58.825
| getTeamsUnreadForUser | Avg| 31ms| 49ms | 18ms | 57.645
| | P99| 447ms| 767ms | 320ms | 71.589
| getThreadsForUser | Avg| 27ms| 42ms | 15ms | 55.752
| | P99| 337ms| 493ms | 156ms | 46.289
| getUser | Avg| 22ms| 38ms | 16ms | 73.143
| | P99| 282ms| 476ms | 194ms | 68.673
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 28ms| 39ms | 11ms | 39.812
| getUsers | Avg| 15ms| 24ms | 9ms | 60.970
| | P99| 226ms| 368ms | 142ms | 62.787
| getUsersByIds | Avg| 3ms| 4ms | 1ms | 29.001
| | P99| 64ms| 86ms | 22ms | 34.293
| getUsersByNames | Avg| 22ms| 30ms | 8ms | 35.763
| | P99| 245ms| 392ms | 147ms | 59.964
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 17ms| 22ms | 5ms | 29.218
| | P99| 239ms| 364ms | 125ms | 52.221
| login | Avg| 236ms| 146ms | -90ms | -38.165
| | P99| 2.161s| 1.234s | -927ms | -42.903
| logout | Avg| 155ms| 132ms | -23ms | -14.793
| | P99| 486ms| 902ms | 416ms | 85.647
| patchPost | Avg| 561ms| 212ms | -349ms | -62.157
| | P99| 1.84s| 2.359s | 519ms | 28.206
| removeUserCustomStatus | Avg| 322ms| 340ms | 18ms | 5.593
| | P99| 1.505s| 2.399s | 894ms | 59.401
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 74ms| 117ms | 43ms | 58.470
| | P99| 830ms| 1.587s | 757ms | 91.151
| searchAllChannels | Avg| 1.396s| 1.38s | -16ms | -1.147
| | P99| 4.851s| 4.83s | -21ms | -0.433
| searchGroupChannels | Avg| 30ms| 44ms | 14ms | 47.400
| | P99| 370ms| 480ms | 110ms | 29.724
| searchPostsInTeam | Avg| 124ms| 140ms | 16ms | 12.897
| | P99| 1.597s| 2.124s | 527ms | 33.002
| searchUsers | Avg| 95ms| 114ms | 19ms | 20.062
| | P99| 718ms| 891ms | 173ms | 24.086
| setPostReminder | Avg| 103ms| 301ms | 198ms | 193.135
| | P99| 815ms| 4.287s | 3.472s | 426.007
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 65ms| 89ms | 24ms | 36.692
| | P99| 450ms| 870ms | 420ms | 93.286
| updateCategoriesForTeamForUser | Avg| 177ms| 230ms | 53ms | 29.893
| | P99| 1.42s| 2.452s | 1.032s | 72.676
| updatePreferences | Avg| 30ms| 31ms | 1ms | 3.374
| | P99| 247ms| 316ms | 69ms | 27.883
| updateReadStateAllThreadsByUser | Avg| 8ms| 22ms | 14ms | 185.022
| | P99| 48ms| 98ms | 50ms | 103.093
| updateReadStateThreadByUser | Avg| 194ms| 306ms | 112ms | 57.761
| | P99| 2.126s| 3.371s | 1.245s | 58.565
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 544ms| 525ms | -19ms | -3.491
| | P99| 2.163s| 2.09s | -73ms | -3.375
| upsertDraft | Avg| 18ms| 25ms | 7ms | 38.921
| | P99| 234ms| 381ms | 147ms | 62.761
| viewChannel | Avg| 63ms| 116ms | 53ms | 84.193
| | P99| 558ms| 1.668s | 1.11s | 199.032
