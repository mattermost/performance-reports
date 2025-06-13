### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | avg | 0s | 20ms | 20ms | 7020796.98
| SessionStore.GetSessionsExpired | avg | 2ms | 6ms | 4ms | 192.16
| LinkMetadataStore.Save | avg | 4ms | 11ms | 7ms | 177.11
| ThreadStore.MarkAllAsReadByTeam | avg | 9ms | 22ms | 13ms | 149.08
| PluginStore.List | avg | 6ms | 10ms | 4ms | 70.09
| EmojiStore.GetMultipleByName | avg | 6ms | 10ms | 4ms | 66.00
| JobStore.UpdateStatusOptimistically | avg | 6ms | 10ms | 4ms | 65.14
| PostPersistentNotificationStore.Get | avg | 6ms | 10ms | 4ms | 64.81
| StatusStore.Get | avg | 5ms | 8ms | 3ms | 58.06
| UserStore.GetProfilesNotInChannel | avg | 13ms | 20ms | 7ms | 53.97
| ChannelStore.GetTeamChannels | avg | 33ms | 48ms | 15ms | 45.76
| JobStore.UpdateStatus | avg | 5ms | 7ms | 2ms | 43.20
| PreferenceStore.DeleteCategoryAndName | avg | 7ms | 10ms | 3ms | 42.64
| PostPriorityStore.GetForPost | avg | 5ms | 7ms | 2ms | 37.31
| RoleStore.ChannelHigherScopedPermissions | avg | 8ms | 11ms | 3ms | 37.09
| CommandWebhookStore.Cleanup | avg | 14ms | 19ms | 5ms | 36.04
| TeamStore.GetTotalMemberCount | avg | 47ms | 62ms | 15ms | 32.06
| ChannelStore.AutocompleteInTeamForSearch | avg | 67ms | 88ms | 21ms | 31.39
| UserStore.Get | avg | 6ms | 8ms | 2ms | 31.37
| ThreadStore.GetTotalUnreadMentions | avg | 6ms | 8ms | 2ms | 30.90
| StatusStore.GetByIds | avg | 11ms | 14ms | 3ms | 27.01
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 12ms | 15ms | 3ms | 24.45
| UserStore.GetMany | avg | 8ms | 10ms | 2ms | 24.40
| ChannelStore.GetAllChannelMembersForUser | avg | 10ms | 12ms | 2ms | 20.59
| JobStore.GetAllByStatus | avg | 10ms | 12ms | 2ms | 19.26
| TokenStore.Cleanup | avg | 16ms | 19ms | 3ms | 18.58
| ChannelStore.GetMemberCount | avg | 27ms | 31ms | 4ms | 14.77
| TeamStore.GetActiveMemberCount | avg | 59ms | 67ms | 8ms | 13.61
| UserStore.AutocompleteUsersInChannel | avg | 60ms | 67ms | 7ms | 11.58
| UserStore.Search | avg | 28ms | 31ms | 3ms | 10.54
| UserStore.Count | avg | 19ms | 21ms | 2ms | 10.31
| PostStore.GetPostsSince | avg | 22ms | 24ms | 2ms | 9.17
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 22ms | 24ms | 2ms | 9.16
| ChannelStore.Autocomplete | avg | 44ms | 48ms | 4ms | 9.03
| UserStore.Save | avg | 82ms | 86ms | 4ms | 4.86
| ChannelStore.CreateDirectChannel | avg | 64ms | 67ms | 3ms | 4.68
| ChannelStore.SaveMember | avg | 45ms | 47ms | 2ms | 4.43
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | p99 | 5ms | 92ms | 87ms | 1757.57
| LinkMetadataStore.Save | p99 | 19ms | 187ms | 168ms | 877.29
| SessionStore.GetSessionsExpired | p99 | 5ms | 46ms | 41ms | 828.28
| UserStore.GetProfilesNotInChannel | p99 | 90ms | 430ms | 340ms | 377.77
| EmojiStore.GetMultipleByName | p99 | 24ms | 94ms | 70ms | 286.89
| ChannelStore.AutocompleteInTeamForSearch | p99 | 379ms | 898ms | 519ms | 136.80
| PostPersistentNotificationStore.Get | p99 | 75ms | 159ms | 84ms | 112.73
| ChannelStore.GetTeamChannels | p99 | 220ms | 465ms | 245ms | 111.36
| ThreadStore.MarkAllAsReadByTeam | p99 | 48ms | 97ms | 49ms | 101.55
| CommandWebhookStore.Cleanup | p99 | 49ms | 97ms | 48ms | 97.96
| TokenStore.Cleanup | p99 | 49ms | 97ms | 48ms | 97.96
| PluginStore.List | p99 | 69ms | 136ms | 67ms | 97.10
| UserStore.Count | p99 | 49ms | 95ms | 46ms | 94.12
| PostPersistentNotificationStore.DeleteExpired | p99 | 37ms | 70ms | 33ms | 88.58
| UserAccessTokenStore.GetByToken | p99 | 48ms | 89ms | 41ms | 85.60
| UserStore.GetByUsername | p99 | 92ms | 168ms | 76ms | 82.95
| PreferenceStore.DeleteCategoryAndName | p99 | 46ms | 82ms | 36ms | 78.05
| RoleStore.ChannelHigherScopedPermissions | p99 | 47ms | 83ms | 36ms | 76.87
| PostPriorityStore.GetForPost | p99 | 50ms | 88ms | 38ms | 76.03
| BotStore.Get | p99 | 46ms | 81ms | 35ms | 75.88
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 47ms | 82ms | 35ms | 73.81
| JobStore.UpdateOptimistically | p99 | 29ms | 50ms | 21ms | 71.77
| JobStore.GetAllByStatus | p99 | 103ms | 176ms | 73ms | 70.72
| JobStore.UpdateStatusOptimistically | p99 | 59ms | 100ms | 41ms | 70.06
| TeamStore.GetMember | p99 | 42ms | 62ms | 20ms | 47.98
| StatusStore.Get | p99 | 70ms | 93ms | 23ms | 32.94
| UserStore.GetMany | p99 | 89ms | 116ms | 27ms | 30.51
| PostAcknowledgementStore.GetForPost | p99 | 60ms | 78ms | 18ms | 30.05
| ChannelStore.GetChannelUnread | p99 | 98ms | 127ms | 29ms | 29.61
| StatusStore.GetByIds | p99 | 134ms | 167ms | 33ms | 24.72
| ChannelStore.GetChannelsByUser | p99 | 65ms | 81ms | 16ms | 24.70
| FileInfoStore.GetByIds | p99 | 95ms | 117ms | 22ms | 23.23
| ChannelStore.GetMemberCount | p99 | 159ms | 193ms | 34ms | 21.34
| PostStore.GetPosts | p99 | 55ms | 66ms | 11ms | 19.88
| ThreadStore.Get | p99 | 76ms | 90ms | 14ms | 18.48
| TeamStore.GetTeamsByUserId | p99 | 72ms | 85ms | 13ms | 17.94
| ChannelStore.UpdateSidebarCategories | p99 | 785ms | 915ms | 130ms | 16.56
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 49ms | 57ms | 8ms | 16.22
| UserStore.Save | p99 | 250ms | 289ms | 39ms | 15.63
| PostStore.GetPostIdAfterTime | p99 | 49ms | 56ms | 7ms | 14.19
| ChannelStore.GetMembersForUserWithPagination | p99 | 71ms | 81ms | 10ms | 14.02
| DraftStore.GetDraftsForUser | p99 | 128ms | 144ms | 16ms | 12.50
| ChannelStore.GetMember | p99 | 80ms | 90ms | 10ms | 12.42
| UserStore.Get | p99 | 84ms | 94ms | 10ms | 11.96
| UserStore.IsEmpty | p99 | 36ms | 40ms | 4ms | 11.22
| UserTermsOfServiceStore.GetByUser | p99 | 71ms | 79ms | 8ms | 11.20
| ChannelStore.GetChannels | p99 | 104ms | 115ms | 11ms | 10.55
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 78ms | 86ms | 8ms | 10.29
| UserStore.GetAllProfiles | p99 | 49ms | 54ms | 5ms | 10.18
| ThreadStore.GetTotalUnreadMentions | p99 | 80ms | 88ms | 8ms | 9.96
| ChannelStore.GetAllChannelMembersForUser | p99 | 91ms | 100ms | 9ms | 9.92
| ChannelStore.Save | p99 | 347ms | 380ms | 33ms | 9.50
| UserStore.UpdateFailedPasswordAttempts | p99 | 75ms | 82ms | 7ms | 9.31
| TeamStore.GetTeamsForUser | p99 | 75ms | 82ms | 7ms | 9.30
| ThreadStore.GetTotalThreads | p99 | 79ms | 86ms | 7ms | 8.84
| TeamStore.GetTotalMemberCount | p99 | 220ms | 239ms | 19ms | 8.64
| ChannelStore.GetMemberLastViewedAt | p99 | 70ms | 76ms | 6ms | 8.62
| PreferenceStore.GetAll | p99 | 82ms | 89ms | 7ms | 8.54
| TeamStore.GetAllPage | p99 | 77ms | 83ms | 6ms | 7.75
| PostStore.GetPostsSince | p99 | 184ms | 198ms | 14ms | 7.62
| ThreadStore.GetTotalUnreadThreads | p99 | 79ms | 85ms | 6ms | 7.59
| SystemStore.GetByName | p99 | 67ms | 72ms | 5ms | 7.43
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 82ms | 88ms | 6ms | 7.36
| DraftStore.Get | p99 | 137ms | 147ms | 10ms | 7.27
| PostStore.GetPostsBefore | p99 | 115ms | 122ms | 7ms | 6.08
| UserStore.GetUnreadCount | p99 | 84ms | 89ms | 5ms | 5.95
| WebhookStore.GetOutgoingByTeam | p99 | 136ms | 144ms | 8ms | 5.88
| FileInfoStore.SetContent | p99 | 200ms | 211ms | 11ms | 5.49
| ThreadStore.GetTeamsUnreadForUser | p99 | 94ms | 99ms | 5ms | 5.31
| SessionStore.GetLRUSessions | p99 | 57ms | 60ms | 3ms | 5.23
| ThreadStore.GetThreadsForUser | p99 | 118ms | 124ms | 6ms | 5.10
| UserStore.GetProfileByIds | p99 | 101ms | 106ms | 5ms | 4.96
| FileInfoStore.Get | p99 | 107ms | 112ms | 5ms | 4.69
| ChannelStore.GetGuestCount | p99 | 86ms | 90ms | 4ms | 4.64
| ChannelStore.Autocomplete | p99 | 219ms | 229ms | 10ms | 4.56
| ThreadStore.GetMembershipForUser | p99 | 90ms | 94ms | 4ms | 4.42
| UserStore.Search | p99 | 209ms | 218ms | 9ms | 4.30
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 48ms | 50ms | 2ms | 4.16
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 73ms | 76ms | 3ms | 4.08
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 204ms | 212ms | 8ms | 3.93
| EmojiStore.GetByName | p99 | 83ms | 86ms | 3ms | 3.61
| ChannelStore.IncrementMentionCount | p99 | 86ms | 89ms | 3ms | 3.47
| TeamStore.GetActiveMemberCount | p99 | 235ms | 242ms | 7ms | 2.98
| ReactionStore.GetForPost | p99 | 77ms | 79ms | 2ms | 2.61
| PostStore.GetPostsByThread | p99 | 91ms | 93ms | 2ms | 2.19
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 93ms | 95ms | 2ms | 2.15
| ChannelStore.GetMemberForPost | p99 | 144ms | 147ms | 3ms | 2.08
| PostStore.GetEtag | p99 | 98ms | 100ms | 2ms | 2.04
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.Get | avg | 6ms | 0s | -6ms | -108.44
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 22ms | 0s | -22ms | -98.97
| StatusStore.SaveOrUpdate | avg | 41ms | 23ms | -18ms | -44.14
| ChannelStore.CreateSidebarCategory | avg | 112ms | 70ms | -42ms | -37.65
| ChannelStore.GetMembers | avg | 6ms | 4ms | -2ms | -33.18
| SessionStore.Remove | avg | 8ms | 6ms | -2ms | -26.04
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 24ms | 19ms | -5ms | -20.72
| PostStore.GetPostReminders | avg | 11ms | 9ms | -2ms | -17.53
| PostStore.Delete | avg | 36ms | 30ms | -6ms | -16.76
| ChannelStore.GetSidebarCategory | avg | 25ms | 21ms | -4ms | -15.74
| PostStore.SetPostReminder | avg | 27ms | 23ms | -4ms | -14.75
| PostStore.AnalyticsPostCount | avg | 342ms | 296ms | -46ms | -13.47
| ThreadStore.MaintainMembership | avg | 17ms | 15ms | -2ms | -11.99
| ChannelStore.UpdateSidebarCategories | avg | 107ms | 101ms | -6ms | -5.63
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.Get | p99 | 59ms | 0s | -59ms | -100.82
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 140ms | 0s | -140ms | -100.29
| PostStore.Delete | p99 | 423ms | 98ms | -325ms | -76.92
| PostStore.GetPostReminders | p99 | 85ms | 41ms | -44ms | -51.76
| StatusStore.SaveOrUpdate | p99 | 732ms | 369ms | -363ms | -49.61
| ChannelStore.CreateSidebarCategory | p99 | 478ms | 243ms | -235ms | -49.21
| SessionStore.Remove | p99 | 81ms | 42ms | -39ms | -48.45
| JobStore.GetNewestJobByStatusesAndType | p99 | 121ms | 65ms | -56ms | -46.28
| ClusterDiscoveryStore.SetLastPingAt | p99 | 155ms | 96ms | -59ms | -38.02
| ChannelStore.GetSidebarCategory | p99 | 285ms | 199ms | -86ms | -30.18
| JobStore.GetCountByStatusAndType | p99 | 121ms | 90ms | -31ms | -25.62
| ChannelStore.GetPublicChannelsForTeam | p99 | 188ms | 146ms | -42ms | -22.34
| JobStore.UpdateStatus | p99 | 59ms | 46ms | -13ms | -22.21
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 243ms | 190ms | -53ms | -21.83
| UserStore.GetAllProfilesInChannel | p99 | 1.518s | 1.195s | -323ms | -21.28
| ChannelStore.CreateInitialSidebarCategories | p99 | 342ms | 273ms | -69ms | -20.20
| PostPersistentNotificationStore.GetSingle | p99 | 74ms | 62ms | -12ms | -16.13
| FileInfoStore.Save | p99 | 156ms | 133ms | -23ms | -14.76
| ChannelStore.SearchGroupChannels | p99 | 139ms | 119ms | -20ms | -14.36
| JobStore.Save | p99 | 58ms | 50ms | -8ms | -13.79
| PostAcknowledgementStore.GetForPosts | p99 | 157ms | 143ms | -14ms | -8.93
| ThreadStore.MarkAsRead | p99 | 81ms | 74ms | -7ms | -8.62
| PostStore.GetPostReminderMetadata | p99 | 85ms | 78ms | -7ms | -8.24
| PostStore.Update | p99 | 245ms | 225ms | -20ms | -8.15
| UserStore.GetProfilesInChannel | p99 | 214ms | 199ms | -15ms | -7.01
| PostStore.SetPostReminder | p99 | 232ms | 216ms | -16ms | -6.90
| ThreadStore.MaintainMembership | p99 | 202ms | 189ms | -13ms | -6.43
| PostStore.GetPostsAfter | p99 | 95ms | 89ms | -6ms | -6.32
| ThreadStore.MarkAllAsReadByChannels | p99 | 95ms | 89ms | -6ms | -6.29
| SessionStore.UpdateLastActivityAt | p99 | 82ms | 77ms | -5ms | -6.13
| TeamStore.Get | p99 | 82ms | 77ms | -5ms | -6.13
| ThreadStore.GetThreadFollowers | p99 | 82ms | 77ms | -5ms | -6.11
| PostStore.Save | p99 | 261ms | 246ms | -15ms | -5.75
| ProductNoticesStore.View | p99 | 473ms | 447ms | -26ms | -5.50
| FileInfoStore.AttachToPost | p99 | 167ms | 158ms | -9ms | -5.38
| StatusStore.UpdateExpiredDNDStatuses | p99 | 205ms | 194ms | -11ms | -5.37
| FileInfoStore.GetForPost | p99 | 95ms | 90ms | -5ms | -5.28
| StatusStore.UpdateLastActivityAt | p99 | 83ms | 79ms | -4ms | -4.79
| PostPriorityStore.GetForPosts | p99 | 160ms | 153ms | -7ms | -4.37
| ThreadStore.UpdateMembership | p99 | 77ms | 74ms | -3ms | -3.89
| PostStore.GetSingle | p99 | 85ms | 82ms | -3ms | -3.52
| ThreadStore.GetThreadForUser | p99 | 173ms | 167ms | -6ms | -3.48
| ChannelStore.UpdateLastViewedAt | p99 | 88ms | 85ms | -3ms | -3.42
| SessionStore.Get | p99 | 185ms | 179ms | -6ms | -3.24
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 93ms | 90ms | -3ms | -3.24
| PreferenceStore.Get | p99 | 100ms | 97ms | -3ms | -3.01
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 87ms | 85ms | -2ms | -2.31
| LinkMetadataStore.Get | p99 | 88ms | 86ms | -2ms | -2.28
| TeamStore.SaveMember | p99 | 230ms | 227ms | -3ms | -1.31
| ChannelStore.CreateDirectChannel | p99 | 477ms | 471ms | -6ms | -1.26
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 9ms | 22ms | 13ms | 147.39
| followThreadByUser | avg | 25ms | 47ms | 22ms | 88.73
| autocompleteChannelsForTeamForSearch | avg | 67ms | 89ms | 22ms | 32.84
| viewChannel | avg | 36ms | 44ms | 8ms | 22.42
| getTeamsUnreadForUser | avg | 12ms | 14ms | 2ms | 16.51
| autocompleteUsers | avg | 56ms | 62ms | 6ms | 10.72
| createChannel | avg | 525ms | 577ms | 52ms | 9.90
| patchPost | avg | 77ms | 84ms | 7ms | 9.10
| searchAllChannels | avg | 45ms | 49ms | 4ms | 8.88
| getCategoriesForTeamForUser | avg | 23ms | 25ms | 2ms | 8.77
| getTeamStats | avg | 66ms | 71ms | 5ms | 7.58
| unfollowThreadByUser | avg | 44ms | 47ms | 3ms | 6.84
| searchUsers | avg | 30ms | 32ms | 2ms | 6.73
| setPostReminder | avg | 62ms | 66ms | 4ms | 6.42
| getPostsForChannelAroundLastUnread | avg | 34ms | 36ms | 2ms | 5.89
| getFilePreview | avg | 62ms | 64ms | 2ms | 3.22
| removeUserCustomStatus | avg | 297ms | 306ms | 9ms | 3.03
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| followThreadByUser | p99 | 94ms | 240ms | 146ms | 155.04
| autocompleteChannelsForTeamForSearch | p99 | 379ms | 898ms | 519ms | 136.80
| updateReadStateAllThreadsByUser | p99 | 48ms | 97ms | 49ms | 101.55
| getTeamMember | p99 | 107ms | 158ms | 51ms | 47.88
| getChannelsForUser | p99 | 69ms | 82ms | 13ms | 18.90
| viewChannel | p99 | 357ms | 409ms | 52ms | 14.58
| getChannelUnread | p99 | 139ms | 158ms | 19ms | 13.68
| getUserStatusesByIds | p99 | 42ms | 47ms | 5ms | 11.99
| getTeamsForUser | p99 | 76ms | 85ms | 9ms | 11.77
| getUser | p99 | 170ms | 185ms | 15ms | 8.82
| getChannelMembersForUser | p99 | 75ms | 81ms | 6ms | 7.97
| getUsers | p99 | 161ms | 173ms | 12ms | 7.45
| getTeamsUnreadForUser | p99 | 176ms | 187ms | 11ms | 6.26
| getPreferences | p99 | 86ms | 91ms | 5ms | 5.83
| getDrafts | p99 | 151ms | 159ms | 8ms | 5.31
| getAllTeams | p99 | 91ms | 95ms | 4ms | 4.37
| searchAllChannels | p99 | 222ms | 231ms | 9ms | 4.05
| searchUsers | p99 | 213ms | 221ms | 8ms | 3.75
| getTeamMembersForUser | p99 | 88ms | 91ms | 3ms | 3.41
| getChannelStats | p99 | 94ms | 97ms | 3ms | 3.19
| upsertDraft | p99 | 174ms | 179ms | 5ms | 2.87
| getCategoriesForTeamForUser | p99 | 212ms | 217ms | 5ms | 2.36
| getThreadsForUser | p99 | 140ms | 143ms | 3ms | 2.15
| getChannelsForTeamForUser | p99 | 120ms | 122ms | 2ms | 1.66
| updateCategoriesForTeamForUser | p99 | 928ms | 943ms | 15ms | 1.62
| getChannelMember | p99 | 196ms | 199ms | 3ms | 1.53
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 10ms | 4ms | -6ms | -61.65
| login | avg | 201ms | 95ms | -106ms | -52.69
| createCategoryForTeamForUser | avg | 144ms | 97ms | -47ms | -32.56
| logout | avg | 121ms | 88ms | -33ms | -27.17
| getChannel | avg | 26ms | 20ms | -6ms | -23.29
| createGroupChannel | avg | 919ms | 715ms | -204ms | -22.20
| createPost | avg | 670ms | 553ms | -117ms | -17.46
| getProfileImage | avg | 83ms | 70ms | -13ms | -15.63
| createDirectChannel | avg | 580ms | 493ms | -87ms | -14.99
| deletePost | avg | 55ms | 49ms | -6ms | -10.89
| createUser | avg | 266ms | 240ms | -26ms | -9.76
| updateCategoriesForTeamForUser | avg | 164ms | 152ms | -12ms | -7.33
| updateReadStateThreadByUser | avg | 119ms | 112ms | -7ms | -5.87
| updatePreferences | avg | 35ms | 33ms | -2ms | -5.75
| uploadFileStream | avg | 591ms | 568ms | -23ms | -3.89
| addChannelMember | avg | 469ms | 454ms | -15ms | -3.20
| searchPostsInTeam | avg | 89ms | 87ms | -2ms | -2.24
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| login | p99 | 2.129s | 516ms | -1.613s | -75.77
| deletePost | p99 | 845ms | 239ms | -606ms | -71.72
| getChannelMembers | p99 | 25ms | 10ms | -15ms | -61.06
| createCategoryForTeamForUser | p99 | 489ms | 246ms | -243ms | -49.72
| createUser | p99 | 1.779s | 994ms | -785ms | -44.12
| createGroupChannel | p99 | 3.89s | 2.451s | -1.439s | -36.99
| createPost | p99 | 3.737s | 2.487s | -1.25s | -33.45
| patchPost | p99 | 781ms | 530ms | -251ms | -32.14
| searchGroupChannels | p99 | 158ms | 124ms | -34ms | -21.46
| updateReadStateThreadByUser | p99 | 768ms | 615ms | -153ms | -19.93
| getPublicChannelsForTeam | p99 | 197ms | 159ms | -38ms | -19.30
| getChannel | p99 | 240ms | 208ms | -32ms | -13.31
| getPostsForChannel | p99 | 915ms | 846ms | -69ms | -7.54
| createDirectChannel | p99 | 2.42s | 2.241s | -179ms | -7.40
| logout | p99 | 480ms | 445ms | -35ms | -7.28
| updatePreferences | p99 | 321ms | 298ms | -23ms | -7.16
| getPostsForChannelAroundLastUnread | p99 | 363ms | 340ms | -23ms | -6.34
| unfollowThreadByUser | p99 | 425ms | 403ms | -22ms | -5.18
| getUsersByNames | p99 | 136ms | 129ms | -7ms | -5.16
| getPostThread | p99 | 436ms | 420ms | -16ms | -3.67
| addTeamMember | p99 | 4.838s | 4.675s | -163ms | -3.37
| getProfileImage | p99 | 484ms | 468ms | -16ms | -3.30
| createChannel | p99 | 2.425s | 2.36s | -65ms | -2.68
| uploadFileStream | p99 | 2.305s | 2.246s | -59ms | -2.56
| getChannelMembersForTeamForUser | p99 | 108ms | 106ms | -2ms | -1.85
| getFilePreview | p99 | 330ms | 325ms | -5ms | -1.51
| searchPostsInTeam | p99 | 2.002s | 1.974s | -28ms | -1.40
| deleteDraft | p99 | 162ms | 160ms | -2ms | -1.23
| addChannelMember | p99 | 2.326s | 2.301s | -25ms | -1.07
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 76ms| 77ms | 1ms | 1.318
| BotStore.Get |  Avg| 6ms| 7ms | 1ms | 17.552
| |  P99| 46ms| 81ms | 35ms | 75.881
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 8ms| 9ms | 1ms | 12.500
| |  P99| 93ms| 95ms | 2ms | 2.148
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 48ms| 50ms | 2ms | 4.157
| ChannelStore.Autocomplete |  Avg| 44ms| 48ms | 4ms | 9.025
| |  P99| 219ms| 229ms | 10ms | 4.563
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 67ms| 88ms | 21ms | 31.388
| |  P99| 379ms| 898ms | 519ms | 136.804
| ChannelStore.CreateDirectChannel |  Avg| 64ms| 67ms | 3ms | 4.681
| |  P99| 477ms| 471ms | -6ms | -1.259
| ChannelStore.CreateInitialSidebarCategories |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 342ms| 273ms | -69ms | -20.205
| ChannelStore.CreateSidebarCategory |  Avg| 112ms| 70ms | -42ms | -37.651
| |  P99| 478ms| 243ms | -235ms | -49.214
| ChannelStore.Get |  Avg| 13ms| 14ms | 1ms | 7.473
| |  P99| 145ms| 146ms | 1ms | 0.691
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 22ms| 0s | -22ms | -98.969
| |  P99| 140ms| 0s | -140ms | -100.286
| ChannelStore.GetAllChannelMembersForUser |  Avg| 10ms| 12ms | 2ms | 20.586
| |  P99| 91ms| 100ms | 9ms | 9.919
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 24ms| 19ms | -5ms | -20.723
| |  P99| 243ms| 190ms | -53ms | -21.830
| ChannelStore.GetByName |  Avg| 9ms| 10ms | 1ms | 10.529
| |  P99| 90ms| 91ms | 1ms | 1.106
| ChannelStore.GetChannelUnread |  Avg| 10ms| 11ms | 1ms | 10.220
| |  P99| 98ms| 127ms | 29ms | 29.608
| ChannelStore.GetChannels |  Avg| 10ms| 11ms | 1ms | 9.680
| |  P99| 104ms| 115ms | 11ms | 10.554
| ChannelStore.GetChannelsByUser |  Avg| 5ms| 6ms | 1ms | 18.690
| |  P99| 65ms| 81ms | 16ms | 24.695
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 9ms| 8ms | -1ms | -11.701
| |  P99| 93ms| 90ms | -3ms | -3.241
| ChannelStore.GetFileCount |  Avg| 10ms| 11ms | 1ms | 10.075
| |  P99| 95ms| 96ms | 1ms | 1.049
| ChannelStore.GetGuestCount |  Avg| 7ms| 8ms | 1ms | 13.643
| |  P99| 86ms| 90ms | 4ms | 4.644
| ChannelStore.GetMember |  Avg| 7ms| 8ms | 1ms | 15.337
| |  P99| 80ms| 90ms | 10ms | 12.425
| ChannelStore.GetMemberCount |  Avg| 27ms| 31ms | 4ms | 14.774
| |  P99| 159ms| 193ms | 34ms | 21.342
| ChannelStore.GetMemberForPost |  Avg| 14ms| 15ms | 1ms | 7.151
| |  P99| 144ms| 147ms | 3ms | 2.083
| ChannelStore.GetMemberLastViewedAt |  Avg| 5ms| 6ms | 1ms | 19.636
| |  P99| 70ms| 76ms | 6ms | 8.621
| ChannelStore.GetMembers |  Avg| 6ms| 4ms | -2ms | -33.176
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 10ms| 11ms | 1ms | 9.531
| |  P99| 99ms| 100ms | 1ms | 1.008
| ChannelStore.GetMembersForUserWithPagination |  Avg| 6ms| 7ms | 1ms | 15.874
| |  P99| 71ms| 81ms | 10ms | 14.016
| ChannelStore.GetPinnedPostCount |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 92ms| 91ms | -1ms | -1.083
| ChannelStore.GetPublicChannelsForTeam |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 188ms| 146ms | -42ms | -22.340
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 22ms| 24ms | 2ms | 9.157
| |  P99| 204ms| 212ms | 8ms | 3.926
| ChannelStore.GetSidebarCategory |  Avg| 25ms| 21ms | -4ms | -15.743
| |  P99| 285ms| 199ms | -86ms | -30.176
| ChannelStore.GetTeamChannels |  Avg| 33ms| 48ms | 15ms | 45.756
| |  P99| 220ms| 465ms | 245ms | 111.361
| ChannelStore.IncrementMentionCount |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 86ms| 89ms | 3ms | 3.470
| ChannelStore.Save |  Avg| 42ms| 42ms | 0s | 0.000
| |  P99| 347ms| 380ms | 33ms | 9.496
| ChannelStore.SaveMember |  Avg| 45ms| 47ms | 2ms | 4.428
| |  P99| 354ms| 354ms | 0s | 0.000
| ChannelStore.SearchGroupChannels |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 139ms| 119ms | -20ms | -14.359
| ChannelStore.UpdateLastViewedAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 88ms| 85ms | -3ms | -3.418
| ChannelStore.UpdateSidebarCategories |  Avg| 107ms| 101ms | -6ms | -5.626
| |  P99| 785ms| 915ms | 130ms | 16.560
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 87ms| 85ms | -2ms | -2.305
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 12ms| 11ms | -1ms | -8.134
| |  P99| 155ms| 96ms | -59ms | -38.015
| CommandWebhookStore.Cleanup |  Avg| 14ms| 19ms | 5ms | 36.043
| |  P99| 49ms| 97ms | 48ms | 97.959
| DraftStore.Delete |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 95ms| 94ms | -1ms | -1.050
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 12ms| 15ms | 3ms | 24.451
| |  P99| 47ms| 82ms | 35ms | 73.814
| DraftStore.Get |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 137ms| 147ms | 10ms | 7.273
| DraftStore.GetDraftsForUser |  Avg| 12ms| 13ms | 1ms | 8.313
| |  P99| 128ms| 144ms | 16ms | 12.504
| DraftStore.Upsert |  Avg| 11ms| 12ms | 1ms | 8.907
| |  P99| 100ms| 99ms | -1ms | -1.003
| EmojiStore.GetByName |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 83ms| 86ms | 3ms | 3.611
| EmojiStore.GetMultipleByName |  Avg| 6ms| 10ms | 4ms | 66.004
| |  P99| 24ms| 94ms | 70ms | 286.885
| FileInfoStore.AttachToPost |  Avg| 15ms| 16ms | 1ms | 6.457
| |  P99| 167ms| 158ms | -9ms | -5.383
| FileInfoStore.Get |  Avg| 10ms| 11ms | 1ms | 9.976
| |  P99| 107ms| 112ms | 5ms | 4.690
| FileInfoStore.GetByIds |  Avg| 9ms| 10ms | 1ms | 11.239
| |  P99| 95ms| 117ms | 22ms | 23.226
| FileInfoStore.GetForPost |  Avg| 9ms| 8ms | -1ms | -11.663
| |  P99| 95ms| 90ms | -5ms | -5.282
| FileInfoStore.Save |  Avg| 13ms| 14ms | 1ms | 7.684
| |  P99| 156ms| 133ms | -23ms | -14.759
| FileInfoStore.SetContent |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 200ms| 211ms | 11ms | 5.494
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 4ms| 5ms | 1ms | 22.328
| |  P99| 49ms| 57ms | 8ms | 16.220
| GroupStore.GetByName |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 79ms| 80ms | 1ms | 1.262
| GroupStore.GetGroups |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 86ms| 85ms | -1ms | -1.162
| JobStore.Get |  Avg| 6ms| 0s | -6ms | -108.436
| |  P99| 59ms| 0s | -59ms | -100.818
| JobStore.GetAllByStatus |  Avg| 10ms| 12ms | 2ms | 19.263
| |  P99| 103ms| 176ms | 73ms | 70.718
| JobStore.GetCountByStatusAndType |  Avg| 9ms| 8ms | -1ms | -10.688
| |  P99| 121ms| 90ms | -31ms | -25.620
| JobStore.GetNewestJobByStatusesAndType |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 121ms| 65ms | -56ms | -46.281
| JobStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 58ms| 50ms | -8ms | -13.793
| JobStore.UpdateOptimistically |  Avg| 5ms| 6ms | 1ms | 18.897
| |  P99| 29ms| 50ms | 21ms | 71.769
| JobStore.UpdateStatus |  Avg| 5ms| 7ms | 2ms | 43.197
| |  P99| 59ms| 46ms | -13ms | -22.214
| JobStore.UpdateStatusOptimistically |  Avg| 6ms| 10ms | 4ms | 65.142
| |  P99| 59ms| 100ms | 41ms | 70.060
| LinkMetadataStore.Get |  Avg| 8ms| 7ms | -1ms | -12.943
| |  P99| 88ms| 86ms | -2ms | -2.277
| LinkMetadataStore.Save |  Avg| 4ms| 11ms | 7ms | 177.106
| |  P99| 19ms| 187ms | 168ms | 877.286
| PluginStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 46ms| 45ms | -1ms | -2.167
| PluginStore.List |  Avg| 6ms| 10ms | 4ms | 70.092
| |  P99| 69ms| 136ms | 67ms | 97.101
| PluginStore.SetWithOptions |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 91ms| 91ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 5ms| 6ms | 1ms | 18.422
| |  P99| 60ms| 78ms | 18ms | 30.050
| PostAcknowledgementStore.GetForPosts |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 157ms| 143ms | -14ms | -8.933
| PostPersistentNotificationStore.DeleteExpired |  Avg| 4ms| 5ms | 1ms | 26.876
| |  P99| 37ms| 70ms | 33ms | 88.575
| PostPersistentNotificationStore.Get |  Avg| 6ms| 10ms | 4ms | 64.808
| |  P99| 75ms| 159ms | 84ms | 112.732
| PostPersistentNotificationStore.GetSingle |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 74ms| 62ms | -12ms | -16.134
| PostPriorityStore.GetForPost |  Avg| 5ms| 7ms | 2ms | 37.313
| |  P99| 50ms| 88ms | 38ms | 76.035
| PostPriorityStore.GetForPosts |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 160ms| 153ms | -7ms | -4.369
| PostStore.AnalyticsPostCount |  Avg| 342ms| 296ms | -46ms | -13.467
| |  P99| 498ms| 498ms | 0s | 0.000
| PostStore.Delete |  Avg| 36ms| 30ms | -6ms | -16.762
| |  P99| 423ms| 98ms | -325ms | -76.923
| PostStore.Get |  Avg| 21ms| 22ms | 1ms | 4.722
| |  P99| 224ms| 222ms | -2ms | -0.893
| PostStore.GetEtag |  Avg| 10ms| 11ms | 1ms | 10.425
| |  P99| 98ms| 100ms | 2ms | 2.045
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 4ms| 5ms | 1ms | 23.291
| |  P99| 49ms| 56ms | 7ms | 14.195
| PostStore.GetPostIdBeforeTime |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 90ms| 90ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 10ms| 9ms | -1ms | -10.227
| |  P99| 85ms| 78ms | -7ms | -8.235
| PostStore.GetPostReminders |  Avg| 11ms| 9ms | -2ms | -17.534
| |  P99| 85ms| 41ms | -44ms | -51.765
| PostStore.GetPosts |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 55ms| 66ms | 11ms | 19.879
| PostStore.GetPostsAfter |  Avg| 11ms| 10ms | -1ms | -9.428
| |  P99| 95ms| 89ms | -6ms | -6.324
| PostStore.GetPostsBefore |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 115ms| 122ms | 7ms | 6.082
| PostStore.GetPostsByThread |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 91ms| 93ms | 2ms | 2.190
| PostStore.GetPostsSince |  Avg| 22ms| 24ms | 2ms | 9.165
| |  P99| 184ms| 198ms | 14ms | 7.622
| PostStore.GetSingle |  Avg| 8ms| 7ms | -1ms | -13.253
| |  P99| 85ms| 82ms | -3ms | -3.521
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 29ms| 30ms | 1ms | 3.404
| |  P99| 261ms| 246ms | -15ms | -5.751
| PostStore.SearchPostsForUser |  Avg| 67ms| 67ms | 0s | 0.000
| |  P99| 1.947s| 1.957s | 10ms | 0.514
| PostStore.SetPostReminder |  Avg| 27ms| 23ms | -4ms | -14.747
| |  P99| 232ms| 216ms | -16ms | -6.897
| PostStore.Update |  Avg| 26ms| 27ms | 1ms | 3.799
| |  P99| 245ms| 225ms | -20ms | -8.155
| PreferenceStore.DeleteCategoryAndName |  Avg| 7ms| 10ms | 3ms | 42.640
| |  P99| 46ms| 82ms | 36ms | 78.049
| PreferenceStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 100ms| 97ms | -3ms | -3.008
| PreferenceStore.GetAll |  Avg| 6ms| 7ms | 1ms | 15.754
| |  P99| 82ms| 89ms | 7ms | 8.538
| PreferenceStore.Save |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 224ms| 223ms | -1ms | -0.445
| ProductNoticesStore.ClearOldNotices |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 57ms| 58ms | 1ms | 1.748
| |  P99| 473ms| 447ms | -26ms | -5.495
| ReactionStore.GetForPost |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 77ms| 79ms | 2ms | 2.610
| RoleStore.ChannelHigherScopedPermissions |  Avg| 8ms| 11ms | 3ms | 37.087
| |  P99| 47ms| 83ms | 36ms | 76.868
| RoleStore.GetByNames |  Avg| 0s| 20ms | 20ms | 7020796.985
| |  P99| 5ms| 92ms | 87ms | 1757.572
| SessionStore.Get |  Avg| 14ms| 13ms | -1ms | -7.226
| |  P99| 185ms| 179ms | -6ms | -3.244
| SessionStore.GetLRUSessions |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 57ms| 60ms | 3ms | 5.227
| SessionStore.GetSessionsExpired |  Avg| 2ms| 6ms | 4ms | 192.162
| |  P99| 5ms| 46ms | 41ms | 828.283
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 6ms| 7ms | 1ms | 15.871
| |  P99| 73ms| 76ms | 3ms | 4.084
| SessionStore.Remove |  Avg| 8ms| 6ms | -2ms | -26.043
| |  P99| 81ms| 42ms | -39ms | -48.447
| SessionStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 95ms| 94ms | -1ms | -1.050
| SessionStore.UpdateLastActivityAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 82ms| 77ms | -5ms | -6.134
| StatusStore.Get |  Avg| 5ms| 8ms | 3ms | 58.059
| |  P99| 70ms| 93ms | 23ms | 32.944
| StatusStore.GetByIds |  Avg| 11ms| 14ms | 3ms | 27.006
| |  P99| 134ms| 167ms | 33ms | 24.719
| StatusStore.SaveOrUpdate |  Avg| 41ms| 23ms | -18ms | -44.143
| |  P99| 732ms| 369ms | -363ms | -49.612
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 11ms| 10ms | -1ms | -9.370
| |  P99| 205ms| 194ms | -11ms | -5.366
| StatusStore.UpdateLastActivityAt |  Avg| 8ms| 7ms | -1ms | -12.747
| |  P99| 83ms| 79ms | -4ms | -4.791
| SystemStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 67ms| 72ms | 5ms | 7.431
| TeamStore.Get |  Avg| 7ms| 6ms | -1ms | -14.410
| |  P99| 82ms| 77ms | -5ms | -6.131
| TeamStore.GetActiveMemberCount |  Avg| 59ms| 67ms | 8ms | 13.605
| |  P99| 235ms| 242ms | 7ms | 2.979
| TeamStore.GetAllPage |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 77ms| 83ms | 6ms | 7.755
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 6ms| 7ms | 1ms | 16.609
| |  P99| 78ms| 86ms | 8ms | 10.290
| TeamStore.GetMember |  Avg| 4ms| 5ms | 1ms | 27.866
| |  P99| 42ms| 62ms | 20ms | 47.984
| TeamStore.GetTeamsByUserId |  Avg| 5ms| 6ms | 1ms | 18.223
| |  P99| 72ms| 85ms | 13ms | 17.935
| TeamStore.GetTeamsForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 75ms| 82ms | 7ms | 9.295
| TeamStore.GetTotalMemberCount |  Avg| 47ms| 62ms | 15ms | 32.059
| |  P99| 220ms| 239ms | 19ms | 8.637
| TeamStore.SaveMember |  Avg| 35ms| 36ms | 1ms | 2.898
| |  P99| 230ms| 227ms | -3ms | -1.306
| ThreadStore.Get |  Avg| 7ms| 8ms | 1ms | 14.488
| |  P99| 76ms| 90ms | 14ms | 18.482
| ThreadStore.GetMembershipForUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 90ms| 94ms | 4ms | 4.422
| ThreadStore.GetTeamsUnreadForUser |  Avg| 8ms| 9ms | 1ms | 12.332
| |  P99| 94ms| 99ms | 5ms | 5.314
| ThreadStore.GetThreadFollowers |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 82ms| 77ms | -5ms | -6.105
| ThreadStore.GetThreadForUser |  Avg| 16ms| 15ms | -1ms | -6.373
| |  P99| 173ms| 167ms | -6ms | -3.477
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 98ms| 99ms | 1ms | 1.016
| ThreadStore.GetThreadsForUser |  Avg| 12ms| 13ms | 1ms | 8.126
| |  P99| 118ms| 124ms | 6ms | 5.097
| ThreadStore.GetTotalThreads |  Avg| 6ms| 7ms | 1ms | 16.050
| |  P99| 79ms| 86ms | 7ms | 8.841
| ThreadStore.GetTotalUnreadMentions |  Avg| 6ms| 8ms | 2ms | 30.896
| |  P99| 80ms| 88ms | 8ms | 9.959
| ThreadStore.GetTotalUnreadThreads |  Avg| 6ms| 7ms | 1ms | 16.021
| |  P99| 79ms| 85ms | 6ms | 7.592
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 82ms| 88ms | 6ms | 7.358
| ThreadStore.MaintainMembership |  Avg| 17ms| 15ms | -2ms | -11.988
| |  P99| 202ms| 189ms | -13ms | -6.431
| ThreadStore.MarkAllAsReadByChannels |  Avg| 9ms| 8ms | -1ms | -10.753
| |  P99| 95ms| 89ms | -6ms | -6.294
| ThreadStore.MarkAllAsReadByTeam |  Avg| 9ms| 22ms | 13ms | 149.079
| |  P99| 48ms| 97ms | 49ms | 101.554
| ThreadStore.MarkAsRead |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 81ms| 74ms | -7ms | -8.620
| ThreadStore.UpdateMembership |  Avg| 8ms| 7ms | -1ms | -12.940
| |  P99| 77ms| 74ms | -3ms | -3.892
| TokenStore.Cleanup |  Avg| 16ms| 19ms | 3ms | 18.579
| |  P99| 49ms| 97ms | 48ms | 97.959
| UserAccessTokenStore.GetByToken |  Avg| 9ms| 8ms | -1ms | -11.245
| |  P99| 48ms| 89ms | 41ms | 85.595
| UserStore.AutocompleteUsersInChannel |  Avg| 60ms| 67ms | 7ms | 11.578
| |  P99| 248ms| 250ms | 2ms | 0.808
| UserStore.Count |  Avg| 19ms| 21ms | 2ms | 10.305
| |  P99| 49ms| 95ms | 46ms | 94.117
| UserStore.Get |  Avg| 6ms| 8ms | 2ms | 31.372
| |  P99| 84ms| 94ms | 10ms | 11.958
| UserStore.GetAllProfiles |  Avg| 5ms| 6ms | 1ms | 18.786
| |  P99| 49ms| 54ms | 5ms | 10.183
| UserStore.GetAllProfilesInChannel |  Avg| 313ms| 310ms | -3ms | -0.958
| |  P99| 1.518s| 1.195s | -323ms | -21.283
| UserStore.GetByUsername |  Avg| 11ms| 12ms | 1ms | 9.512
| |  P99| 92ms| 168ms | 76ms | 82.947
| UserStore.GetForLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 75ms| 75ms | 0s | 0.000
| UserStore.GetMany |  Avg| 8ms| 10ms | 2ms | 24.404
| |  P99| 89ms| 116ms | 27ms | 30.508
| UserStore.GetProfileByIds |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 101ms| 106ms | 5ms | 4.961
| UserStore.GetProfilesByUsernames |  Avg| 11ms| 12ms | 1ms | 9.240
| |  P99| 115ms| 116ms | 1ms | 0.873
| UserStore.GetProfilesInChannel |  Avg| 18ms| 19ms | 1ms | 5.619
| |  P99| 214ms| 199ms | -15ms | -7.009
| UserStore.GetProfilesNotInChannel |  Avg| 13ms| 20ms | 7ms | 53.973
| |  P99| 90ms| 430ms | 340ms | 377.774
| UserStore.GetUnreadCount |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 84ms| 89ms | 5ms | 5.955
| UserStore.IsEmpty |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 36ms| 40ms | 4ms | 11.224
| UserStore.Save |  Avg| 82ms| 86ms | 4ms | 4.858
| |  P99| 250ms| 289ms | 39ms | 15.629
| UserStore.Search |  Avg| 28ms| 31ms | 3ms | 10.539
| |  P99| 209ms| 218ms | 9ms | 4.300
| UserStore.Update |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 217ms| 217ms | 0s | 0.000
| UserStore.UpdateFailedPasswordAttempts |  Avg| 7ms| 8ms | 1ms | 14.587
| |  P99| 75ms| 82ms | 7ms | 9.308
| UserStore.UpdateLastLogin |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 49ms| 48ms | -1ms | -2.061
| UserStore.UpdateUpdateAt |  Avg| 6ms| 7ms | 1ms | 15.542
| |  P99| 48ms| 48ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 5ms| 6ms | 1ms | 19.200
| |  P99| 71ms| 79ms | 8ms | 11.200
| WebhookStore.GetOutgoingByTeam |  Avg| 12ms| 13ms | 1ms | 8.013
| |  P99| 136ms| 144ms | 8ms | 5.882
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 469ms| 454ms | -15ms | -3.197
| | P99| 2.326s| 2.301s | -25ms | -1.075
| addTeamMember | Avg| 1.03s| 1.026s | -4ms | -0.388
| | P99| 4.838s| 4.675s | -163ms | -3.369
| autocompleteChannelsForTeamForSearch | Avg| 67ms| 89ms | 22ms | 32.838
| | P99| 379ms| 898ms | 519ms | 136.804
| autocompleteUsers | Avg| 56ms| 62ms | 6ms | 10.725
| | P99| 249ms| 250ms | 1ms | 0.402
| createCategoryForTeamForUser | Avg| 144ms| 97ms | -47ms | -32.555
| | P99| 489ms| 246ms | -243ms | -49.719
| createChannel | Avg| 525ms| 577ms | 52ms | 9.902
| | P99| 2.425s| 2.36s | -65ms | -2.680
| createDirectChannel | Avg| 580ms| 493ms | -87ms | -14.995
| | P99| 2.42s| 2.241s | -179ms | -7.397
| createGroupChannel | Avg| 919ms| 715ms | -204ms | -22.202
| | P99| 3.89s| 2.451s | -1.439s | -36.992
| createPost | Avg| 670ms| 553ms | -117ms | -17.456
| | P99| 3.737s| 2.487s | -1.25s | -33.450
| createUser | Avg| 266ms| 240ms | -26ms | -9.762
| | P99| 1.779s| 994ms | -785ms | -44.120
| deleteDraft | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 162ms| 160ms | -2ms | -1.235
| deletePost | Avg| 55ms| 49ms | -6ms | -10.890
| | P99| 845ms| 239ms | -606ms | -71.715
| followThreadByUser | Avg| 25ms| 47ms | 22ms | 88.731
| | P99| 94ms| 240ms | 146ms | 155.044
| getAllTeams | Avg| 7ms| 8ms | 1ms | 14.520
| | P99| 91ms| 95ms | 4ms | 4.373
| getCategoriesForTeamForUser | Avg| 23ms| 25ms | 2ms | 8.770
| | P99| 212ms| 217ms | 5ms | 2.358
| getChannel | Avg| 26ms| 20ms | -6ms | -23.294
| | P99| 240ms| 208ms | -32ms | -13.314
| getChannelMember | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 196ms| 199ms | 3ms | 1.532
| getChannelMembers | Avg| 10ms| 4ms | -6ms | -61.646
| | P99| 25ms| 10ms | -15ms | -61.061
| getChannelMembersForTeamForUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 108ms| 106ms | -2ms | -1.846
| getChannelMembersForUser | Avg| 7ms| 8ms | 1ms | 15.259
| | P99| 75ms| 81ms | 6ms | 7.972
| getChannelStats | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 94ms| 97ms | 3ms | 3.194
| getChannelUnread | Avg| 11ms| 12ms | 1ms | 8.730
| | P99| 139ms| 158ms | 19ms | 13.682
| getChannelsForTeamForUser | Avg| 11ms| 12ms | 1ms | 9.315
| | P99| 120ms| 122ms | 2ms | 1.664
| getChannelsForUser | Avg| 6ms| 7ms | 1ms | 18.056
| | P99| 69ms| 82ms | 13ms | 18.896
| getClientConfig | Avg| 15ms| 16ms | 1ms | 6.689
| | P99| 206ms| 206ms | 0s | 0.000
| getDrafts | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 151ms| 159ms | 8ms | 5.313
| getFilePreview | Avg| 62ms| 64ms | 2ms | 3.221
| | P99| 330ms| 325ms | -5ms | -1.513
| getFileThumbnail | Avg| 53ms| 53ms | 0s | 0.000
| | P99| 248ms| 247ms | -1ms | -0.403
| getPostThread | Avg| 50ms| 50ms | 0s | 0.000
| | P99| 436ms| 420ms | -16ms | -3.668
| getPostsForChannel | Avg| 90ms| 90ms | 0s | 0.000
| | P99| 915ms| 846ms | -69ms | -7.539
| getPostsForChannelAroundLastUnread | Avg| 34ms| 36ms | 2ms | 5.887
| | P99| 363ms| 340ms | -23ms | -6.341
| getPreferences | Avg| 7ms| 8ms | 1ms | 14.929
| | P99| 86ms| 91ms | 5ms | 5.827
| getProfileImage | Avg| 83ms| 70ms | -13ms | -15.630
| | P99| 484ms| 468ms | -16ms | -3.305
| getPublicChannelsForTeam | Avg| 27ms| 27ms | 0s | 0.000
| | P99| 197ms| 159ms | -38ms | -19.303
| getTeamMember | Avg| 10ms| 11ms | 1ms | 9.727
| | P99| 107ms| 158ms | 51ms | 47.878
| getTeamMembersForUser | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 88ms| 91ms | 3ms | 3.409
| getTeamStats | Avg| 66ms| 71ms | 5ms | 7.579
| | P99| 240ms| 242ms | 2ms | 0.833
| getTeamsForUser | Avg| 6ms| 7ms | 1ms | 17.447
| | P99| 76ms| 85ms | 9ms | 11.769
| getTeamsUnreadForUser | Avg| 12ms| 14ms | 2ms | 16.505
| | P99| 176ms| 187ms | 11ms | 6.259
| getThreadsForUser | Avg| 12ms| 13ms | 1ms | 8.219
| | P99| 140ms| 143ms | 3ms | 2.146
| getUser | Avg| 9ms| 10ms | 1ms | 11.073
| | P99| 170ms| 185ms | 15ms | 8.821
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 42ms| 47ms | 5ms | 11.990
| getUsers | Avg| 9ms| 10ms | 1ms | 10.819
| | P99| 161ms| 173ms | 12ms | 7.455
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 42ms| 41ms | -1ms | -2.376
| getUsersByNames | Avg| 11ms| 12ms | 1ms | 8.735
| | P99| 136ms| 129ms | -7ms | -5.160
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 99ms| 100ms | 1ms | 1.011
| login | Avg| 201ms| 95ms | -106ms | -52.691
| | P99| 2.129s| 516ms | -1.613s | -75.768
| logout | Avg| 121ms| 88ms | -33ms | -27.167
| | P99| 480ms| 445ms | -35ms | -7.284
| patchPost | Avg| 77ms| 84ms | 7ms | 9.105
| | P99| 781ms| 530ms | -251ms | -32.138
| removeUserCustomStatus | Avg| 297ms| 306ms | 9ms | 3.027
| | P99| 984ms| 977ms | -7ms | -0.711
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 31ms| 32ms | 1ms | 3.206
| | P99| 242ms| 242ms | 0s | 0.000
| searchAllChannels | Avg| 45ms| 49ms | 4ms | 8.876
| | P99| 222ms| 231ms | 9ms | 4.054
| searchGroupChannels | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 158ms| 124ms | -34ms | -21.461
| searchPostsInTeam | Avg| 89ms| 87ms | -2ms | -2.240
| | P99| 2.002s| 1.974s | -28ms | -1.398
| searchUsers | Avg| 30ms| 32ms | 2ms | 6.734
| | P99| 213ms| 221ms | 8ms | 3.747
| setPostReminder | Avg| 62ms| 66ms | 4ms | 6.415
| | P99| 440ms| 444ms | 4ms | 0.909
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 44ms| 47ms | 3ms | 6.843
| | P99| 425ms| 403ms | -22ms | -5.177
| updateCategoriesForTeamForUser | Avg| 164ms| 152ms | -12ms | -7.332
| | P99| 928ms| 943ms | 15ms | 1.616
| updatePreferences | Avg| 35ms| 33ms | -2ms | -5.752
| | P99| 321ms| 298ms | -23ms | -7.155
| updateReadStateAllThreadsByUser | Avg| 9ms| 22ms | 13ms | 147.391
| | P99| 48ms| 97ms | 49ms | 101.554
| updateReadStateThreadByUser | Avg| 119ms| 112ms | -7ms | -5.875
| | P99| 768ms| 615ms | -153ms | -19.926
| updateUserCustomStatus | Avg| 1ms| 0s | -1ms | -151.867
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 591ms| 568ms | -23ms | -3.889
| | P99| 2.305s| 2.246s | -59ms | -2.559
| upsertDraft | Avg| 14ms| 15ms | 1ms | 7.178
| | P99| 174ms| 179ms | 5ms | 2.873
| viewChannel | Avg| 36ms| 44ms | 8ms | 22.416
| | P99| 357ms| 409ms | 52ms | 14.583
