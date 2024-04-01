### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetMany | avg | 1ms | 19ms | 18ms | 1358.73
| StatusStore.SaveOrUpdate | avg | 3ms | 34ms | 31ms | 1182.30
| ChannelStore.GetAllChannelMembersForUser | avg | 2ms | 11ms | 9ms | 494.28
| ThreadStore.Get | avg | 1ms | 3ms | 2ms | 175.30
| PostStore.GetPostReminderMetadata | avg | 1ms | 3ms | 2ms | 168.51
| PostStore.GetPostsAfter | avg | 3ms | 8ms | 5ms | 151.36
| JobStore.Get | avg | 2ms | 5ms | 3ms | 140.64
| PluginStore.List | avg | 5ms | 8ms | 3ms | 57.30
| PostPriorityStore.GetForPost | avg | 7ms | 11ms | 4ms | 55.81
| UserStore.GetUnreadCount | avg | 8ms | 10ms | 2ms | 24.78
| ChannelStore.CreateSidebarCategory | avg | 10ms | 12ms | 2ms | 20.69
| ChannelStore.GetTeamChannels | avg | 41ms | 47ms | 6ms | 14.46
| PostStore.SearchPostsForUser | avg | 65ms | 67ms | 2ms | 3.09
| ChannelStore.GetMemberCount | avg | 215ms | 219ms | 4ms | 1.86
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetMany | p99 | 5ms | 232ms | 227ms | 4585.86
| StatusStore.SaveOrUpdate | p99 | 10ms | 444ms | 434ms | 4470.57
| ThreadStore.Get | p99 | 5ms | 83ms | 78ms | 1575.76
| PostStore.GetPostsAfter | p99 | 22ms | 202ms | 180ms | 825.71
| PostStore.GetPostReminderMetadata | p99 | 5ms | 44ms | 39ms | 787.88
| JobStore.Get | p99 | 38ms | 185ms | 147ms | 386.84
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 68ms | 164ms | 96ms | 141.95
| ChannelStore.GetAllChannelMembersForUser | p99 | 40ms | 92ms | 52ms | 129.75
| ChannelStore.GetPublicChannelsForTeam | p99 | 99ms | 180ms | 81ms | 82.11
| ChannelStore.GetMemberForPost | p99 | 89ms | 150ms | 61ms | 68.28
| JobStore.Save | p99 | 5ms | 8ms | 3ms | 60.61
| ChannelStore.CreateDirectChannel | p99 | 481ms | 725ms | 244ms | 50.70
| FileInfoStore.AttachToPost | p99 | 10ms | 14ms | 4ms | 41.04
| ChannelStore.SearchGroupChannels | p99 | 132ms | 168ms | 36ms | 27.31
| PostStore.Update | p99 | 30ms | 38ms | 8ms | 26.67
| PostPriorityStore.GetForPost | p99 | 180ms | 215ms | 35ms | 19.50
| ChannelStore.GetGuestCount | p99 | 304ms | 353ms | 49ms | 16.10
| PluginStore.List | p99 | 190ms | 218ms | 28ms | 14.74
| EmojiStore.GetByName | p99 | 142ms | 158ms | 16ms | 11.30
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 77ms | 85ms | 8ms | 10.42
| UserStore.IsEmpty | p99 | 174ms | 190ms | 16ms | 9.19
| WebhookStore.GetOutgoingByTeam | p99 | 144ms | 157ms | 13ms | 9.00
| PreferenceStore.Save | p99 | 28ms | 30ms | 2ms | 7.16
| ThreadStore.GetMembershipForUser | p99 | 98ms | 104ms | 6ms | 6.11
| TeamStore.SaveMember | p99 | 385ms | 405ms | 20ms | 5.19
| UserTermsOfServiceStore.GetByUser | p99 | 232ms | 243ms | 11ms | 4.73
| PostStore.Get | p99 | 174ms | 182ms | 8ms | 4.60
| UserStore.GetProfilesByUsernames | p99 | 132ms | 136ms | 4ms | 3.04
| SessionStore.Save | p99 | 232ms | 239ms | 7ms | 3.01
| TeamStore.GetTeamsForUser | p99 | 233ms | 240ms | 7ms | 3.01
| PreferenceStore.GetAll | p99 | 242ms | 248ms | 6ms | 2.48
| ChannelStore.GetChannelsByUser | p99 | 392ms | 401ms | 9ms | 2.30
| StatusStore.Get | p99 | 218ms | 223ms | 5ms | 2.29
| ChannelStore.GetByName | p99 | 224ms | 229ms | 5ms | 2.23
| PreferenceStore.Get | p99 | 139ms | 142ms | 3ms | 2.15
| TeamStore.GetTeamsByUserId | p99 | 237ms | 242ms | 5ms | 2.11
| SessionStore.Get | p99 | 240ms | 245ms | 5ms | 2.09
| UserStore.GetForLogin | p99 | 233ms | 237ms | 4ms | 1.72
| PostStore.GetEtag | p99 | 234ms | 238ms | 4ms | 1.71
| ChannelStore.SaveMember | p99 | 868ms | 881ms | 13ms | 1.50
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | avg | 3ms | 0s | -3ms | -104.07
| SessionStore.GetLRUSessions | avg | 17ms | 0s | -17ms | -102.37
| BotStore.Save | avg | 4ms | 0s | -4ms | -97.35
| TeamStore.GetByName | avg | 8ms | 0s | -8ms | -95.13
| ChannelStore.GetChannelUnread | avg | 6ms | 1ms | -5ms | -89.93
| ChannelStore.GetMembers | avg | 2ms | 0s | -2ms | -88.83
| ChannelStore.GetSidebarCategory | avg | 12ms | 2ms | -10ms | -81.12
| StatusStore.GetByIds | avg | 7ms | 2ms | -5ms | -76.15
| UserAccessTokenStore.GetByToken | avg | 9ms | 2ms | -7ms | -74.04
| ChannelStore.GetPinnedPostCount | avg | 10ms | 3ms | -7ms | -72.86
| JobStore.GetCountByStatusAndType | avg | 11ms | 4ms | -7ms | -63.53
| UserStore.GetByUsername | avg | 8ms | 4ms | -4ms | -51.14
| JobStore.GetNewestJobByStatusesAndType | avg | 15ms | 8ms | -7ms | -46.85
| ChannelStore.UpdateSidebarCategories | avg | 28ms | 17ms | -11ms | -38.72
| ReactionStore.GetForPost | avg | 5ms | 3ms | -2ms | -37.28
| TeamStore.Get | avg | 6ms | 4ms | -2ms | -35.91
| ChannelStore.GetChannelsByUser | avg | 53ms | 37ms | -16ms | -30.21
| GroupStore.GetGroups | avg | 10ms | 7ms | -3ms | -29.17
| ThreadStore.GetTotalUnreadThreads | avg | 15ms | 11ms | -4ms | -27.37
| TeamStore.GetTeamsForUser | avg | 18ms | 13ms | -5ms | -27.25
| BotStore.Get | avg | 11ms | 8ms | -3ms | -27.16
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 18ms | 13ms | -5ms | -27.16
| UserStore.GetAllProfiles | avg | 15ms | 11ms | -4ms | -26.80
| TeamStore.GetTeamsByUserId | avg | 19ms | 14ms | -5ms | -26.19
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 58ms | 43ms | -15ms | -25.92
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 16ms | 12ms | -4ms | -25.61
| ChannelStore.Get | avg | 12ms | 9ms | -3ms | -24.82
| TeamStore.GetChannelUnreadsForAllTeams | avg | 17ms | 13ms | -4ms | -24.15
| PostStore.GetPosts | avg | 21ms | 16ms | -5ms | -24.11
| ChannelStore.GetMemberLastViewedAt | avg | 17ms | 13ms | -4ms | -23.85
| ThreadStore.GetTotalUnreadMentions | avg | 13ms | 10ms | -3ms | -23.63
| ThreadStore.GetTeamsUnreadForUser | avg | 17ms | 13ms | -4ms | -23.49
| PostPriorityStore.GetForPosts | avg | 9ms | 7ms | -2ms | -23.05
| TeamStore.GetAllPage | avg | 17ms | 13ms | -4ms | -22.92
| StatusStore.Get | avg | 14ms | 11ms | -3ms | -21.63
| ThreadStore.GetTotalThreads | avg | 15ms | 12ms | -3ms | -20.37
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 15ms | 12ms | -3ms | -19.90
| ChannelStore.GetMembersForUser | avg | 10ms | 8ms | -2ms | -19.54
| GroupStore.GetByName | avg | 16ms | 13ms | -3ms | -18.33
| UserStore.GetForLogin | avg | 17ms | 14ms | -3ms | -17.31
| ChannelStore.SaveMember | avg | 87ms | 72ms | -15ms | -17.26
| UserTermsOfServiceStore.GetByUser | avg | 18ms | 15ms | -3ms | -17.03
| SessionStore.Get | avg | 20ms | 17ms | -3ms | -15.14
| SessionStore.Save | avg | 21ms | 18ms | -3ms | -14.54
| PreferenceStore.GetAll | avg | 22ms | 19ms | -3ms | -13.67
| ChannelStore.GetByName | avg | 15ms | 13ms | -2ms | -13.61
| ChannelStore.GetPublicChannelsForTeam | avg | 16ms | 14ms | -2ms | -12.89
| ChannelStore.GetGuestCount | avg | 25ms | 22ms | -3ms | -11.78
| ChannelStore.CreateInitialSidebarCategories | avg | 26ms | 23ms | -3ms | -11.54
| ChannelStore.AutocompleteInTeamForSearch | avg | 141ms | 125ms | -16ms | -11.33
| ChannelStore.CreateDirectChannel | avg | 28ms | 26ms | -2ms | -7.02
| UserStore.GetAllProfilesInChannel | avg | 553ms | 516ms | -37ms | -6.70
| ChannelStore.Autocomplete | avg | 1.635s | 1.536s | -99ms | -6.05
| UserStore.AnalyticsActiveCount | avg | 220ms | 207ms | -13ms | -5.90
| UserStore.AutocompleteUsersInChannel | avg | 214ms | 208ms | -6ms | -2.80
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.InvalidateChannelByName | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetForPost | p99 | 5ms | 0s | -5ms | -101.01
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.Save | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.InvalidateAllChannelMembersForUser | p99 | 5ms | 0s | -5ms | -101.01
| ProductNoticesStore.ClearOldNotices | p99 | 5ms | 0s | -5ms | -100.98
| TeamStore.GetByName | p99 | 201ms | 0s | -201ms | -100.25
| SessionStore.GetLRUSessions | p99 | 231ms | 0s | -231ms | -99.83
| ChannelStore.GetSidebarCategory | p99 | 202ms | 5ms | -197ms | -97.52
| ChannelStore.GetChannelUnread | p99 | 87ms | 5ms | -82ms | -93.72
| StatusStore.GetByIds | p99 | 93ms | 8ms | -85ms | -91.28
| UserAccessTokenStore.GetByToken | p99 | 225ms | 21ms | -204ms | -90.87
| ReactionStore.GetForPost | p99 | 79ms | 10ms | -69ms | -87.73
| ChannelStore.UpdateSidebarCategories | p99 | 238ms | 47ms | -191ms | -80.25
| PostPersistentNotificationStore.Get | p99 | 21ms | 5ms | -16ms | -77.48
| ChannelStore.GetPinnedPostCount | p99 | 215ms | 49ms | -166ms | -77.32
| JobStore.UpdateStatusOptimistically | p99 | 38ms | 9ms | -29ms | -76.32
| JobStore.UpdateStatus | p99 | 18ms | 5ms | -13ms | -73.03
| JobStore.UpdateOptimistically | p99 | 18ms | 5ms | -13ms | -73.03
| FileInfoStore.GetForPost | p99 | 96ms | 27ms | -69ms | -71.64
| FileInfoStore.Get | p99 | 82ms | 27ms | -55ms | -66.87
| PostStore.SetPostReminder | p99 | 10ms | 5ms | -5ms | -50.63
| ChannelStore.GetTeamChannels | p99 | 97ms | 50ms | -47ms | -48.45
| LinkMetadataStore.Save | p99 | 17ms | 9ms | -8ms | -46.92
| PostPersistentNotificationStore.DeleteExpired | p99 | 9ms | 5ms | -4ms | -46.78
| FileInfoStore.SetContent | p99 | 19ms | 10ms | -9ms | -46.50
| PostStore.GetSingle | p99 | 120ms | 69ms | -51ms | -42.57
| LinkMetadataStore.Get | p99 | 125ms | 73ms | -52ms | -41.65
| ChannelStore.AutocompleteInTeamForSearch | p99 | 1.125s | 688ms | -437ms | -38.85
| JobStore.GetCountByStatusAndType | p99 | 226ms | 140ms | -86ms | -38.14
| JobStore.GetNewestJobByStatusesAndType | p99 | 255ms | 163ms | -92ms | -36.08
| ClusterDiscoveryStore.SetLastPingAt | p99 | 12ms | 8ms | -4ms | -34.33
| TeamStore.Get | p99 | 157ms | 110ms | -47ms | -29.86
| ChannelStore.GetFileCount | p99 | 161ms | 117ms | -44ms | -27.30
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 213ms | 157ms | -56ms | -26.25
| ChannelStore.Autocomplete | p99 | 8.241s | 6.391s | -1.85s | -22.45
| UserStore.Get | p99 | 9ms | 7ms | -2ms | -21.88
| PostStore.GetPostIdAfterTime | p99 | 16ms | 13ms | -3ms | -18.59
| UserStore.GetByUsername | p99 | 201ms | 169ms | -32ms | -15.96
| PostAcknowledgementStore.GetForPosts | p99 | 212ms | 182ms | -30ms | -14.17
| PostStore.GetPostsByThread | p99 | 61ms | 53ms | -8ms | -13.02
| PostPriorityStore.GetForPosts | p99 | 216ms | 188ms | -28ms | -12.94
| JobStore.GetAllByStatus | p99 | 134ms | 117ms | -17ms | -12.68
| GroupStore.GetGroups | p99 | 216ms | 189ms | -27ms | -12.48
| ProductNoticesStore.View | p99 | 97ms | 85ms | -12ms | -12.38
| ThreadStore.GetThreadsForUser | p99 | 187ms | 165ms | -22ms | -11.79
| PostStore.GetPostsSince | p99 | 191ms | 173ms | -18ms | -9.44
| UserStore.AutocompleteUsersInChannel | p99 | 928ms | 845ms | -83ms | -8.95
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 737ms | 674ms | -63ms | -8.55
| PostPersistentNotificationStore.GetSingle | p99 | 161ms | 151ms | -10ms | -6.19
| UserStore.Count | p99 | 440ms | 415ms | -25ms | -5.68
| PostStore.GetPostsBefore | p99 | 175ms | 166ms | -9ms | -5.14
| PostStore.SearchPostsForUser | p99 | 489ms | 464ms | -25ms | -5.11
| PostAcknowledgementStore.GetForPost | p99 | 188ms | 180ms | -8ms | -4.24
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 149ms | 143ms | -6ms | -4.04
| ChannelStore.Get | p99 | 234ms | 225ms | -9ms | -3.84
| ThreadStore.GetTeamsUnreadForUser | p99 | 236ms | 227ms | -9ms | -3.82
| ChannelStore.GetMembersForUser | p99 | 213ms | 205ms | -8ms | -3.76
| ThreadStore.GetThreadForUser | p99 | 195ms | 188ms | -7ms | -3.58
| UserStore.GetAllProfilesInChannel | p99 | 2.415s | 2.347s | -68ms | -2.82
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 231ms | 226ms | -5ms | -2.17
| ChannelStore.GetChannels | p99 | 215ms | 211ms | -4ms | -1.86
| ChannelStore.GetMemberCount | p99 | 954ms | 939ms | -15ms | -1.57
| UserStore.GetAllProfiles | p99 | 202ms | 199ms | -3ms | -1.49
| BotStore.Get | p99 | 224ms | 221ms | -3ms | -1.34
| PostStore.GetPosts | p99 | 241ms | 238ms | -3ms | -1.25
| ChannelStore.Save | p99 | 176ms | 174ms | -2ms | -1.13
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| unfollowThreadByUser | avg | 6ms | 9ms | 3ms | 49.55
| getChannel | avg | 8ms | 11ms | 3ms | 39.69
| createCategoryForTeamForUser | avg | 11ms | 15ms | 4ms | 36.13
| createChannel | avg | 42ms | 47ms | 5ms | 12.01
| getProfileImage | avg | 83ms | 91ms | 8ms | 9.58
| createUser | avg | 111ms | 121ms | 10ms | 8.97
| getLicenseSelfServeStatus | avg | 170ms | 179ms | 9ms | 5.30
| createGroupChannel | avg | 277ms | 291ms | 14ms | 5.06
| uploadFileStream | avg | 382ms | 401ms | 19ms | 4.97
| addChannelMember | avg | 230ms | 236ms | 6ms | 2.61
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| unfollowThreadByUser | p99 | 10ms | 88ms | 78ms | 783.81
| getChannel | p99 | 99ms | 258ms | 159ms | 160.40
| getPublicChannelsForTeam | p99 | 99ms | 180ms | 81ms | 82.11
| searchGroupChannels | p99 | 132ms | 168ms | 36ms | 27.31
| updateReadStateThreadByUser | p99 | 490ms | 596ms | 106ms | 21.64
| viewChannel | p99 | 252ms | 282ms | 30ms | 11.89
| saveReaction | p99 | 427ms | 474ms | 47ms | 11.00
| getTeamMembersForUser | p99 | 240ms | 256ms | 16ms | 6.66
| createUser | p99 | 464ms | 493ms | 29ms | 6.24
| addChannelMember | p99 | 1.915s | 2.025s | 110ms | 5.74
| getUser | p99 | 242ms | 255ms | 13ms | 5.36
| getProfileImage | p99 | 431ms | 453ms | 22ms | 5.10
| getUsersByNames | p99 | 132ms | 136ms | 4ms | 3.04
| getChannelsForUser | p99 | 393ms | 404ms | 11ms | 2.80
| getPreferences | p99 | 244ms | 249ms | 5ms | 2.05
| getTeamsForUser | p99 | 238ms | 242ms | 4ms | 1.68
| getAllTeams | p99 | 240ms | 244ms | 4ms | 1.67
| getChannelMember | p99 | 399ms | 405ms | 6ms | 1.50
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 3ms | 0s | -3ms | -100.58
| updateReadStateAllThreadsByUser | avg | 3ms | 0s | -3ms | -100.55
| getRolesByNames | avg | 3ms | 1ms | -2ms | -75.42
| getChannelUnread | avg | 6ms | 2ms | -4ms | -68.32
| updateCategoriesForTeamForUser | avg | 63ms | 23ms | -40ms | -63.25
| getUsers | avg | 17ms | 10ms | -7ms | -41.11
| getChannelsForUser | avg | 54ms | 38ms | -16ms | -29.68
| getTeamsForUser | avg | 19ms | 14ms | -5ms | -26.11
| getTeamMembersForUser | avg | 20ms | 15ms | -5ms | -24.77
| getCategoriesForTeamForUser | avg | 58ms | 44ms | -14ms | -24.00
| getTeamsUnreadForUser | avg | 26ms | 20ms | -6ms | -22.68
| getPostsForChannelAroundLastUnread | avg | 92ms | 72ms | -20ms | -21.75
| getAllTeams | avg | 19ms | 15ms | -4ms | -21.34
| getThreadsForUser | avg | 10ms | 8ms | -2ms | -20.56
| getUser | avg | 21ms | 17ms | -4ms | -19.29
| getPostsForChannel | avg | 43ms | 35ms | -8ms | -18.62
| getChannelMembersForTeamForUser | avg | 11ms | 9ms | -2ms | -18.37
| login | avg | 96ms | 80ms | -16ms | -16.63
| getChannelsForTeamForUser | avg | 12ms | 10ms | -2ms | -16.04
| getPreferences | avg | 22ms | 19ms | -3ms | -13.37
| createPost | avg | 471ms | 411ms | -60ms | -12.73
| getFileThumbnail | avg | 33ms | 29ms | -4ms | -12.09
| getPublicChannelsForTeam | avg | 17ms | 15ms | -2ms | -11.96
| getChannelMember | avg | 26ms | 23ms | -3ms | -11.63
| getChannelStats | avg | 26ms | 23ms | -3ms | -11.35
| autocompleteChannelsForTeamForSearch | avg | 141ms | 125ms | -16ms | -11.32
| getFilePreview | avg | 39ms | 35ms | -4ms | -10.32
| patchPost | avg | 35ms | 32ms | -3ms | -8.68
| addTeamMember | avg | 1.595s | 1.473s | -122ms | -7.65
| removeUserCustomStatus | avg | 131ms | 123ms | -8ms | -6.12
| searchAllChannels | avg | 1.635s | 1.536s | -99ms | -6.05
| createDirectChannel | avg | 197ms | 186ms | -11ms | -5.59
| autocompleteUsers | avg | 170ms | 161ms | -9ms | -5.30
| searchPostsInTeam | avg | 73ms | 71ms | -2ms | -2.74
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| getChannelUnread | p99 | 87ms | 5ms | -82ms | -93.72
| updateCategoriesForTeamForUser | p99 | 460ms | 49ms | -411ms | -89.35
| getFileThumbnail | p99 | 223ms | 99ms | -124ms | -55.50
| createChannel | p99 | 97ms | 50ms | -47ms | -48.45
| createDirectChannel | p99 | 983ms | 515ms | -468ms | -47.63
| autocompleteChannelsForTeamForSearch | p99 | 1.125s | 688ms | -437ms | -38.85
| getChannelStats | p99 | 745ms | 558ms | -187ms | -25.09
| searchAllChannels | p99 | 8.241s | 6.391s | -1.85s | -22.45
| getFilePreview | p99 | 234ms | 182ms | -52ms | -22.22
| getPostThread | p99 | 445ms | 360ms | -85ms | -19.12
| getPostsForChannel | p99 | 847ms | 687ms | -160ms | -18.88
| login | p99 | 828ms | 693ms | -135ms | -16.31
| patchPost | p99 | 600ms | 505ms | -95ms | -15.83
| autocompleteUsers | p99 | 870ms | 748ms | -122ms | -14.03
| getUsers | p99 | 216ms | 196ms | -20ms | -9.25
| getCategoriesForTeamForUser | p99 | 740ms | 682ms | -58ms | -7.84
| searchPostsInTeam | p99 | 685ms | 645ms | -40ms | -5.84
| getThreadsForUser | p99 | 209ms | 197ms | -12ms | -5.74
| addTeamMember | p99 | 6.477s | 6.161s | -316ms | -4.88
| getChannelMembersForTeamForUser | p99 | 221ms | 212ms | -9ms | -4.07
| getChannelsForTeamForUser | p99 | 241ms | 232ms | -9ms | -3.74
| getTeamsUnreadForUser | p99 | 392ms | 383ms | -9ms | -2.30
| getClientConfig | p99 | 101ms | 99ms | -2ms | -1.98
| createPost | p99 | 2.478s | 2.439s | -39ms | -1.57
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.748
| BotStore.Get |  Avg| 11ms| 8ms | -3ms | -27.158
| |  P99| 224ms| 221ms | -3ms | -1.336
| BotStore.Save |  Avg| 4ms| 0s | -4ms | -97.352
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| ChannelStore.AnalyticsTypeCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 1.635s| 1.536s | -99ms | -6.055
| |  P99| 8.241s| 6.391s | -1.85s | -22.449
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 141ms| 125ms | -16ms | -11.326
| |  P99| 1.125s| 688ms | -437ms | -38.845
| ChannelStore.CreateDirectChannel |  Avg| 28ms| 26ms | -2ms | -7.019
| |  P99| 481ms| 725ms | 244ms | 50.700
| ChannelStore.CreateInitialSidebarCategories |  Avg| 26ms| 23ms | -3ms | -11.542
| |  P99| 241ms| 243ms | 2ms | 0.832
| ChannelStore.CreateSidebarCategory |  Avg| 10ms| 12ms | 2ms | 20.694
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Get |  Avg| 12ms| 9ms | -3ms | -24.816
| |  P99| 234ms| 225ms | -9ms | -3.844
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 18ms| 13ms | -5ms | -27.157
| |  P99| 213ms| 157ms | -56ms | -26.247
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 11ms | 9ms | 494.281
| |  P99| 40ms| 92ms | 52ms | 129.749
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 18ms| 19ms | 1ms | 5.618
| |  P99| 68ms| 164ms | 96ms | 141.947
| ChannelStore.GetByName |  Avg| 15ms| 13ms | -2ms | -13.606
| |  P99| 224ms| 229ms | 5ms | 2.228
| ChannelStore.GetChannelUnread |  Avg| 6ms| 1ms | -5ms | -89.927
| |  P99| 87ms| 5ms | -82ms | -93.717
| ChannelStore.GetChannels |  Avg| 10ms| 9ms | -1ms | -9.664
| |  P99| 215ms| 211ms | -4ms | -1.863
| ChannelStore.GetChannelsByUser |  Avg| 53ms| 37ms | -16ms | -30.212
| |  P99| 392ms| 401ms | 9ms | 2.298
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 149ms| 143ms | -6ms | -4.040
| ChannelStore.GetFileCount |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 161ms| 117ms | -44ms | -27.299
| ChannelStore.GetForPost |  Avg| 1ms| 0s | -1ms | -94.922
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetGuestCount |  Avg| 25ms| 22ms | -3ms | -11.783
| |  P99| 304ms| 353ms | 49ms | 16.102
| ChannelStore.GetMember |  Avg| 1ms| 2ms | 1ms | 71.760
| |  P99| 17ms| 18ms | 1ms | 5.977
| ChannelStore.GetMemberCount |  Avg| 215ms| 219ms | 4ms | 1.859
| |  P99| 954ms| 939ms | -15ms | -1.572
| ChannelStore.GetMemberForPost |  Avg| 4ms| 5ms | 1ms | 27.144
| |  P99| 89ms| 150ms | 61ms | 68.278
| ChannelStore.GetMemberLastViewedAt |  Avg| 17ms| 13ms | -4ms | -23.847
| |  P99| 233ms| 233ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 2ms| 0s | -2ms | -88.829
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 10ms| 8ms | -2ms | -19.538
| |  P99| 213ms| 205ms | -8ms | -3.756
| ChannelStore.GetMembersForUserWithPagination |  Avg| 12ms| 13ms | 1ms | 8.056
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 10ms| 3ms | -7ms | -72.862
| |  P99| 215ms| 49ms | -166ms | -77.323
| ChannelStore.GetPublicChannelsForTeam |  Avg| 16ms| 14ms | -2ms | -12.888
| |  P99| 99ms| 180ms | 81ms | 82.111
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 58ms| 43ms | -15ms | -25.925
| |  P99| 737ms| 674ms | -63ms | -8.546
| ChannelStore.GetSidebarCategory |  Avg| 12ms| 2ms | -10ms | -81.117
| |  P99| 202ms| 5ms | -197ms | -97.521
| ChannelStore.GetTeamChannels |  Avg| 41ms| 47ms | 6ms | 14.458
| |  P99| 97ms| 50ms | -47ms | -48.454
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.973
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.005
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.Save |  Avg| 11ms| 12ms | 1ms | 9.122
| |  P99| 176ms| 174ms | -2ms | -1.133
| ChannelStore.SaveMember |  Avg| 87ms| 72ms | -15ms | -17.258
| |  P99| 868ms| 881ms | 13ms | 1.498
| ChannelStore.SearchGroupChannels |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 132ms| 168ms | 36ms | 27.312
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 28ms| 17ms | -11ms | -38.721
| |  P99| 238ms| 47ms | -191ms | -80.251
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 2ms | -1ms | -39.745
| |  P99| 12ms| 8ms | -4ms | -34.326
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 1ms| 2ms | 1ms | 67.937
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 142ms| 158ms | 16ms | 11.304
| EmojiStore.GetMultipleByName |  Avg| 2ms| 1ms | -1ms | -50.762
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 3ms| 4ms | 1ms | 28.736
| |  P99| 10ms| 14ms | 4ms | 41.038
| FileInfoStore.Get |  Avg| 3ms| 2ms | -1ms | -29.869
| |  P99| 82ms| 27ms | -55ms | -66.869
| FileInfoStore.GetForPost |  Avg| 4ms| 3ms | -1ms | -24.675
| |  P99| 96ms| 27ms | -69ms | -71.644
| FileInfoStore.Save |  Avg| 3ms| 4ms | 1ms | 28.783
| |  P99| 10ms| 10ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 19ms| 10ms | -9ms | -46.502
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 16ms| 12ms | -4ms | -25.606
| |  P99| 231ms| 226ms | -5ms | -2.165
| GroupStore.GetByName |  Avg| 16ms| 13ms | -3ms | -18.334
| |  P99| 231ms| 233ms | 2ms | 0.866
| GroupStore.GetGroups |  Avg| 10ms| 7ms | -3ms | -29.170
| |  P99| 216ms| 189ms | -27ms | -12.477
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 2ms| 5ms | 3ms | 140.642
| |  P99| 38ms| 185ms | 147ms | 386.842
| JobStore.GetAllByStatus |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 134ms| 117ms | -17ms | -12.676
| JobStore.GetCountByStatusAndType |  Avg| 11ms| 4ms | -7ms | -63.526
| |  P99| 226ms| 140ms | -86ms | -38.137
| JobStore.GetNewestJobByStatusesAndType |  Avg| 15ms| 8ms | -7ms | -46.845
| |  P99| 255ms| 163ms | -92ms | -36.078
| JobStore.Save |  Avg| 3ms| 2ms | -1ms | -38.637
| |  P99| 5ms| 8ms | 3ms | 60.606
| JobStore.UpdateOptimistically |  Avg| 3ms| 2ms | -1ms | -37.965
| |  P99| 18ms| 5ms | -13ms | -73.034
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 5ms | -13ms | -73.034
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 3ms | -1ms | -26.234
| |  P99| 38ms| 9ms | -29ms | -76.316
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 4ms| 3ms | -1ms | -22.995
| |  P99| 125ms| 73ms | -52ms | -41.650
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 9ms | -8ms | -46.918
| PluginStore.Delete |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 5ms| 8ms | 3ms | 57.299
| |  P99| 190ms| 218ms | 28ms | 14.737
| PluginStore.SetWithOptions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.882
| PostAcknowledgementStore.GetForPost |  Avg| 9ms| 8ms | -1ms | -11.175
| |  P99| 188ms| 180ms | -8ms | -4.244
| PostAcknowledgementStore.GetForPosts |  Avg| 8ms| 7ms | -1ms | -11.768
| |  P99| 212ms| 182ms | -30ms | -14.166
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.784
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 21ms| 5ms | -16ms | -77.482
| PostPersistentNotificationStore.GetSingle |  Avg| 6ms| 5ms | -1ms | -17.566
| |  P99| 161ms| 151ms | -10ms | -6.192
| PostPriorityStore.GetForPost |  Avg| 7ms| 11ms | 4ms | 55.810
| |  P99| 180ms| 215ms | 35ms | 19.498
| PostPriorityStore.GetForPosts |  Avg| 9ms| 7ms | -2ms | -23.049
| |  P99| 216ms| 188ms | -28ms | -12.944
| PostStore.Delete |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Get |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 174ms| 182ms | 8ms | 4.601
| PostStore.GetEtag |  Avg| 13ms| 12ms | -1ms | -7.555
| |  P99| 234ms| 238ms | 4ms | 1.706
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 13ms | -3ms | -18.595
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 3ms | 2ms | 168.506
| |  P99| 5ms| 44ms | 39ms | 787.879
| PostStore.GetPostReminders |  Avg| 3ms| 4ms | 1ms | 28.664
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 21ms| 16ms | -5ms | -24.111
| |  P99| 241ms| 238ms | -3ms | -1.245
| PostStore.GetPostsAfter |  Avg| 3ms| 8ms | 5ms | 151.365
| |  P99| 22ms| 202ms | 180ms | 825.709
| PostStore.GetPostsBefore |  Avg| 8ms| 7ms | -1ms | -13.052
| |  P99| 175ms| 166ms | -9ms | -5.138
| PostStore.GetPostsByThread |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 61ms| 53ms | -8ms | -13.024
| PostStore.GetPostsSince |  Avg| 13ms| 12ms | -1ms | -7.899
| |  P99| 191ms| 173ms | -18ms | -9.443
| PostStore.GetSingle |  Avg| 4ms| 3ms | -1ms | -22.441
| |  P99| 120ms| 69ms | -51ms | -42.566
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 65ms| 67ms | 2ms | 3.089
| |  P99| 489ms| 464ms | -25ms | -5.109
| PostStore.SetPostReminder |  Avg| 4ms| 3ms | -1ms | -26.027
| |  P99| 10ms| 5ms | -5ms | -50.633
| PostStore.Update |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 30ms| 38ms | 8ms | 26.671
| PreferenceStore.DeleteCategoryAndName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 139ms| 142ms | 3ms | 2.155
| PreferenceStore.GetAll |  Avg| 22ms| 19ms | -3ms | -13.666
| |  P99| 242ms| 248ms | 6ms | 2.483
| PreferenceStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 28ms| 30ms | 2ms | 7.164
| ProductNoticesStore.ClearOldNotices |  Avg| 1ms| 0s | -1ms | -89.988
| |  P99| 5ms| 0s | -5ms | -100.984
| ProductNoticesStore.GetViews |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 97ms| 85ms | -12ms | -12.384
| ReactionStore.GetForPost |  Avg| 5ms| 3ms | -2ms | -37.279
| |  P99| 79ms| 10ms | -69ms | -87.727
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 1ms| 0s | -1ms | -86.160
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 20ms| 17ms | -3ms | -15.135
| |  P99| 240ms| 245ms | 5ms | 2.088
| SessionStore.GetLRUSessions |  Avg| 17ms| 0s | -17ms | -102.367
| |  P99| 231ms| 0s | -231ms | -99.832
| SessionStore.GetSessionsExpired |  Avg| 2ms| 1ms | -1ms | -59.743
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 3ms| 4ms | 1ms | 29.805
| |  P99| 77ms| 85ms | 8ms | 10.423
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 21ms| 18ms | -3ms | -14.538
| |  P99| 232ms| 239ms | 7ms | 3.013
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| StatusStore.Get |  Avg| 14ms| 11ms | -3ms | -21.633
| |  P99| 218ms| 223ms | 5ms | 2.295
| StatusStore.GetByIds |  Avg| 7ms| 2ms | -5ms | -76.149
| |  P99| 93ms| 8ms | -85ms | -91.276
| StatusStore.SaveOrUpdate |  Avg| 3ms| 34ms | 31ms | 1182.303
| |  P99| 10ms| 444ms | 434ms | 4470.575
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.800
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 6ms| 4ms | -2ms | -35.914
| |  P99| 157ms| 110ms | -47ms | -29.860
| TeamStore.GetAllPage |  Avg| 17ms| 13ms | -4ms | -22.924
| |  P99| 234ms| 236ms | 2ms | 0.855
| TeamStore.GetByName |  Avg| 8ms| 0s | -8ms | -95.130
| |  P99| 201ms| 0s | -201ms | -100.249
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 17ms| 13ms | -4ms | -24.145
| |  P99| 231ms| 231ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 19ms| 14ms | -5ms | -26.191
| |  P99| 237ms| 242ms | 5ms | 2.108
| TeamStore.GetTeamsForUser |  Avg| 18ms| 13ms | -5ms | -27.250
| |  P99| 233ms| 240ms | 7ms | 3.006
| TeamStore.SaveMember |  Avg| 107ms| 106ms | -1ms | -0.934
| |  P99| 385ms| 405ms | 20ms | 5.195
| ThreadStore.Get |  Avg| 1ms| 3ms | 2ms | 175.304
| |  P99| 5ms| 83ms | 78ms | 1575.758
| ThreadStore.GetMembershipForUser |  Avg| 5ms| 4ms | -1ms | -21.318
| |  P99| 98ms| 104ms | 6ms | 6.106
| ThreadStore.GetTeamsUnreadForUser |  Avg| 17ms| 13ms | -4ms | -23.489
| |  P99| 236ms| 227ms | -9ms | -3.822
| ThreadStore.GetThreadFollowers |  Avg| 6ms| 5ms | -1ms | -16.606
| |  P99| 163ms| 163ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 8ms| 7ms | -1ms | -12.880
| |  P99| 195ms| 188ms | -7ms | -3.584
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 72ms| 73ms | 1ms | 1.393
| ThreadStore.GetThreadsForUser |  Avg| 7ms| 6ms | -1ms | -14.025
| |  P99| 187ms| 165ms | -22ms | -11.788
| ThreadStore.GetTotalThreads |  Avg| 15ms| 12ms | -3ms | -20.365
| |  P99| 226ms| 226ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 13ms| 10ms | -3ms | -23.631
| |  P99| 219ms| 217ms | -2ms | -0.914
| ThreadStore.GetTotalUnreadThreads |  Avg| 15ms| 11ms | -4ms | -27.374
| |  P99| 226ms| 224ms | -2ms | -0.883
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 15ms| 12ms | -3ms | -19.897
| |  P99| 228ms| 229ms | 1ms | 0.438
| ThreadStore.MaintainMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 1ms| 2ms | 1ms | 92.636
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 0s | -3ms | -104.067
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 15.143
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.916
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 9ms| 2ms | -7ms | -74.044
| |  P99| 225ms| 21ms | -204ms | -90.866
| UserStore.AnalyticsActiveCount |  Avg| 220ms| 207ms | -13ms | -5.901
| |  P99| 248ms| 249ms | 1ms | 0.402
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 214ms| 208ms | -6ms | -2.803
| |  P99| 928ms| 845ms | -83ms | -8.945
| UserStore.Count |  Avg| 99ms| 100ms | 1ms | 1.012
| |  P99| 440ms| 415ms | -25ms | -5.682
| UserStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -21.878
| UserStore.GetAllProfiles |  Avg| 15ms| 11ms | -4ms | -26.796
| |  P99| 202ms| 199ms | -3ms | -1.486
| UserStore.GetAllProfilesInChannel |  Avg| 553ms| 516ms | -37ms | -6.696
| |  P99| 2.415s| 2.347s | -68ms | -2.816
| UserStore.GetByUsername |  Avg| 8ms| 4ms | -4ms | -51.142
| |  P99| 201ms| 169ms | -32ms | -15.960
| UserStore.GetForLogin |  Avg| 17ms| 14ms | -3ms | -17.312
| |  P99| 233ms| 237ms | 4ms | 1.719
| UserStore.GetMany |  Avg| 1ms| 19ms | 18ms | 1358.732
| |  P99| 5ms| 232ms | 227ms | 4585.859
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.541
| UserStore.GetProfilesByUsernames |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 132ms| 136ms | 4ms | 3.039
| UserStore.GetUnreadCount |  Avg| 8ms| 10ms | 2ms | 24.784
| |  P99| 254ms| 253ms | -1ms | -0.394
| UserStore.IsEmpty |  Avg| 10ms| 9ms | -1ms | -9.524
| |  P99| 174ms| 190ms | 16ms | 9.185
| UserStore.Save |  Avg| 67ms| 67ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| UserStore.Search |  Avg| 94ms| 95ms | 1ms | 1.061
| |  P99| 463ms| 462ms | -1ms | -0.216
| UserStore.Update |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.036
| UserStore.UpdateFailedPasswordAttempts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.768
| UserStore.UpdateLastLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.176
| UserStore.UpdateUpdateAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.328
| UserTermsOfServiceStore.GetByUser |  Avg| 18ms| 15ms | -3ms | -17.034
| |  P99| 232ms| 243ms | 11ms | 4.731
| WebhookStore.GetOutgoingByTeam |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 144ms| 157ms | 13ms | 9.001
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 230ms| 236ms | 6ms | 2.606
| | P99| 1.915s| 2.025s | 110ms | 5.744
| addTeamMember | Avg| 1.595s| 1.473s | -122ms | -7.649
| | P99| 6.477s| 6.161s | -316ms | -4.879
| autocompleteChannelsForTeamForSearch | Avg| 141ms| 125ms | -16ms | -11.322
| | P99| 1.125s| 688ms | -437ms | -38.845
| autocompleteUsers | Avg| 170ms| 161ms | -9ms | -5.299
| | P99| 870ms| 748ms | -122ms | -14.026
| createCategoryForTeamForUser | Avg| 11ms| 15ms | 4ms | 36.126
| | P99| 25ms| 25ms | 0s | 0.000
| createChannel | Avg| 42ms| 47ms | 5ms | 12.010
| | P99| 97ms| 50ms | -47ms | -48.454
| createDirectChannel | Avg| 197ms| 186ms | -11ms | -5.592
| | P99| 983ms| 515ms | -468ms | -47.631
| createGroupChannel | Avg| 277ms| 291ms | 14ms | 5.056
| | P99| 2.132s| 2.118s | -14ms | -0.657
| createPost | Avg| 471ms| 411ms | -60ms | -12.726
| | P99| 2.478s| 2.439s | -39ms | -1.574
| createUser | Avg| 111ms| 121ms | 10ms | 8.969
| | P99| 464ms| 493ms | 29ms | 6.244
| deletePost | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getAllTeams | Avg| 19ms| 15ms | -4ms | -21.337
| | P99| 240ms| 244ms | 4ms | 1.670
| getCategoriesForTeamForUser | Avg| 58ms| 44ms | -14ms | -24.002
| | P99| 740ms| 682ms | -58ms | -7.842
| getChannel | Avg| 8ms| 11ms | 3ms | 39.687
| | P99| 99ms| 258ms | 159ms | 160.398
| getChannelMember | Avg| 26ms| 23ms | -3ms | -11.630
| | P99| 399ms| 405ms | 6ms | 1.503
| getChannelMembers | Avg| 3ms| 0s | -3ms | -100.583
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 11ms| 9ms | -2ms | -18.367
| | P99| 221ms| 212ms | -9ms | -4.070
| getChannelMembersForUser | Avg| 14ms| 13ms | -1ms | -7.299
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelStats | Avg| 26ms| 23ms | -3ms | -11.351
| | P99| 745ms| 558ms | -187ms | -25.085
| getChannelUnread | Avg| 6ms| 2ms | -4ms | -68.324
| | P99| 87ms| 5ms | -82ms | -93.717
| getChannelsForTeamForUser | Avg| 12ms| 10ms | -2ms | -16.043
| | P99| 241ms| 232ms | -9ms | -3.740
| getChannelsForUser | Avg| 54ms| 38ms | -16ms | -29.683
| | P99| 393ms| 404ms | 11ms | 2.797
| getClientConfig | Avg| 6ms| 5ms | -1ms | -17.051
| | P99| 101ms| 99ms | -2ms | -1.976
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 39ms| 35ms | -4ms | -10.318
| | P99| 234ms| 182ms | -52ms | -22.219
| getFileThumbnail | Avg| 33ms| 29ms | -4ms | -12.090
| | P99| 223ms| 99ms | -124ms | -55.500
| getGroups | Avg| 1ms| 2ms | 1ms | 71.511
| | P99| 5ms| 5ms | 0s | 0.000
| getLicenseSelfServeStatus | Avg| 170ms| 179ms | 9ms | 5.299
| | P99| 249ms| 249ms | 0s | 0.000
| getPostThread | Avg| 17ms| 16ms | -1ms | -6.015
| | P99| 445ms| 360ms | -85ms | -19.122
| getPostsForChannel | Avg| 43ms| 35ms | -8ms | -18.620
| | P99| 847ms| 687ms | -160ms | -18.881
| getPostsForChannelAroundLastUnread | Avg| 92ms| 72ms | -20ms | -21.750
| | P99| 992ms| 984ms | -8ms | -0.806
| getPreferences | Avg| 22ms| 19ms | -3ms | -13.374
| | P99| 244ms| 249ms | 5ms | 2.049
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProductNotices | Avg| 2ms| 1ms | -1ms | -62.545
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 83ms| 91ms | 8ms | 9.585
| | P99| 431ms| 453ms | 22ms | 5.103
| getPublicChannelsForTeam | Avg| 17ms| 15ms | -2ms | -11.957
| | P99| 99ms| 180ms | 81ms | 82.111
| getRolesByNames | Avg| 3ms| 1ms | -2ms | -75.416
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 20ms| 15ms | -5ms | -24.770
| | P99| 240ms| 256ms | 16ms | 6.662
| getTeamsForUser | Avg| 19ms| 14ms | -5ms | -26.113
| | P99| 238ms| 242ms | 4ms | 1.683
| getTeamsUnreadForUser | Avg| 26ms| 20ms | -6ms | -22.677
| | P99| 392ms| 383ms | -9ms | -2.295
| getThreadsForUser | Avg| 10ms| 8ms | -2ms | -20.560
| | P99| 209ms| 197ms | -12ms | -5.742
| getUser | Avg| 21ms| 17ms | -4ms | -19.292
| | P99| 242ms| 255ms | 13ms | 5.364
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 17ms| 10ms | -7ms | -41.110
| | P99| 216ms| 196ms | -20ms | -9.252
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 132ms| 136ms | 4ms | 3.035
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 96ms| 80ms | -16ms | -16.634
| | P99| 828ms| 693ms | -135ms | -16.311
| logout | Avg| 32ms| 33ms | 1ms | 3.139
| | P99| 50ms| 50ms | 0s | 0.000
| patchPost | Avg| 35ms| 32ms | -3ms | -8.680
| | P99| 600ms| 505ms | -95ms | -15.831
| removeUserCustomStatus | Avg| 131ms| 123ms | -8ms | -6.122
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 1ms | 1ms | 890.846
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 427ms| 474ms | 47ms | 11.003
| searchAllChannels | Avg| 1.635s| 1.536s | -99ms | -6.054
| | P99| 8.241s| 6.391s | -1.85s | -22.449
| searchGroupChannels | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 132ms| 168ms | 36ms | 27.312
| searchPostsInTeam | Avg| 73ms| 71ms | -2ms | -2.741
| | P99| 685ms| 645ms | -40ms | -5.839
| searchUsers | Avg| 96ms| 97ms | 1ms | 1.044
| | P99| 469ms| 472ms | 3ms | 0.640
| setPostReminder | Avg| 11ms| 10ms | -1ms | -9.408
| | P99| 25ms| 25ms | 0s | 0.000
| unfollowThreadByUser | Avg| 6ms| 9ms | 3ms | 49.548
| | P99| 10ms| 88ms | 78ms | 783.807
| updateCategoriesForTeamForUser | Avg| 63ms| 23ms | -40ms | -63.246
| | P99| 460ms| 49ms | -411ms | -89.347
| updatePreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 3ms| 0s | -3ms | -100.547
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 27ms| 28ms | 1ms | 3.673
| | P99| 490ms| 596ms | 106ms | 21.637
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 382ms| 401ms | 19ms | 4.968
| | P99| 988ms| 997ms | 9ms | 0.911
| viewChannel | Avg| 15ms| 14ms | -1ms | -6.780
| | P99| 252ms| 282ms | 30ms | 11.890
